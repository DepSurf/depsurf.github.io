# Function: <code>show_signal</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579042204,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:229",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038480,
      "name": "show_signal.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071579042204,
      "name": "show_signal.isra.9.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579049820,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:230",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579046144,
      "name": "show_signal.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071579049820,
      "name": "show_signal.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579052060,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:230",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048384,
      "name": "show_signal.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071579052060,
      "name": "show_signal.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591154555,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:137",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579059961,
      "name": "show_signal.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591647837,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:141",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591244453,
      "name": "show_signal.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591591676,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:141",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591188157,
      "name": "show_signal.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592763467,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:141",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592051412,
      "name": "show_signal.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579118002,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:143",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:gp_user_force_sig_segv",
        "arch/x86/kernel/traps.c:do_trap"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:gp_user_force_sig_segv",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593818004,
      "name": "show_signal.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void show_signal(struct task_struct * tsk, int signr, const char * type, const char * desc, struct pt_regs * regs, long int error_code)
```

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596389838,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:145",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_general_protection"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156848,
      "name": "show_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
void show_signal(struct task_struct * tsk, int signr, const char * type, const char * desc, struct pt_regs * regs, long int error_code)
```

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596920053,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:145",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_general_protection"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579159008,
      "name": "show_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
void show_signal(struct task_struct * tsk, int signr, const char * type, const char * desc, struct pt_regs * regs, long int error_code)
```

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597845773,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:134",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_general_protection"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188320,
      "name": "show_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579052412,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:230",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048736,
      "name": "show_signal.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071579052412,
      "name": "show_signal.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578985173,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:230",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981872,
      "name": "show_signal.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071578985173,
      "name": "show_signal.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579051996,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:230",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048320,
      "name": "show_signal.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071579051996,
      "name": "show_signal.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_signal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579055932,
      "name": "show_signal",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:230",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_bounds",
        "arch/x86/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052096,
      "name": "show_signal.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071579055932,
      "name": "show_signal.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void show_signal(struct task_struct * tsk, int signr, const char * type, const char * desc, struct pt_regs * regs, long int error_code)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
