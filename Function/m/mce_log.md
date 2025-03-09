# Function: <code>mce_log</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mce_log(struct mce * mce)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579127792,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:155",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_inject_log",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_log_therm_throt_event",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127792,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
void mce_log(struct mce * mce)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579127904,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:154",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_log_therm_throt_event",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_inject_log",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127904,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void mce_log(struct mce * mce)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579135024,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:159",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_log_therm_throt_event",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_inject_log",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579135024,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579133728,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:135",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_inject_log",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579133728,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579148624,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:144",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_inject_log",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148624,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579158528,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:139",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_inject_log",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158528,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579148016,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:137",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_inject_log",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148016,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579160640,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:154",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_inject_log",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160640,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163104,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:154",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_inject_log",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163104,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579183308,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:156",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579177616,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579179888,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:156",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579174240,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579185984,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:156",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181184,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579220288,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:156",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215120,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594665747,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:142",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269168,
      "name": "mce_log",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596399827,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:142",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331776,
      "name": "mce_log",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596930896,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:136",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579340608,
      "name": "mce_log",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597856624,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:138",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error",
        "arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370736,
      "name": "mce_log",
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163456,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:154",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_inject_log",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163456,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579095024,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:154",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_inject_log",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579095024,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163024,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:154",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_inject_log",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163024,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mce_log(struct mce * m)
```

```json
{
  "name": "mce_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579168208,
      "name": "mce_log",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:154",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_inject_log",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579168208,
      "name": "mce_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mce * m</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mce * mce</code>
</li>
</ul>
</details>
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
void mce_log(struct mce * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void mce_log(struct mce * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void mce_log(struct mce * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void mce_log(struct mce * m)
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
