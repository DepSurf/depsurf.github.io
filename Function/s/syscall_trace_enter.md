# Function: <code>syscall_trace_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578860432,
      "name": "syscall_trace_enter",
      "external": true,
      "loc": "arch/x86/entry/common.c:211",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_syscall_32_irqs_off",
        "arch/x86/entry/common.c:do_fast_syscall_32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578860432,
      "name": "syscall_trace_enter",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578858208,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "arch/x86/entry/common.c:70",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858208,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 745
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
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578858176,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "arch/x86/entry/common.c:63",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858176,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
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
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578857840,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "arch/x86/entry/common.c:65",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857840,
      "name": "syscall_trace_enter",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578857664,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "arch/x86/entry/common.c:67",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857664,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578859680,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "arch/x86/entry/common.c:67",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578859680,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578860896,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "arch/x86/entry/common.c:67",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578860896,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578860448,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "arch/x86/entry/common.c:69",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578860448,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578860448,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "arch/x86/entry/common.c:69",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578860448,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578866560,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "arch/x86/entry/common.c:156",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_syscall_32_irqs_on",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578866560,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580136304,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "kernel/entry/common.c:43",
      "file": "kernel/entry/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:syscall_enter_from_user_mode",
        "kernel/entry/common.c:syscall_enter_from_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136304,
      "name": "syscall_trace_enter.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580141136,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "kernel/entry/common.c:44",
      "file": "kernel/entry/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:syscall_enter_from_user_mode",
        "kernel/entry/common.c:syscall_enter_from_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141136,
      "name": "syscall_trace_enter.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580284784,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "kernel/entry/common.c:44",
      "file": "kernel/entry/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:syscall_enter_from_user_mode",
        "kernel/entry/common.c:syscall_enter_from_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284784,
      "name": "syscall_trace_enter.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580458224,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "kernel/entry/common.c:46",
      "file": "kernel/entry/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:syscall_enter_from_user_mode",
        "kernel/entry/common.c:syscall_enter_from_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580458224,
      "name": "syscall_trace_enter.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580705280,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "kernel/entry/common.c:48",
      "file": "kernel/entry/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:syscall_enter_from_user_mode",
        "kernel/entry/common.c:syscall_enter_from_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705280,
      "name": "syscall_trace_enter.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580782112,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "kernel/entry/common.c:48",
      "file": "kernel/entry/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:syscall_enter_from_user_mode",
        "kernel/entry/common.c:syscall_enter_from_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782112,
      "name": "syscall_trace_enter.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
long int syscall_trace_enter(struct pt_regs * regs, long int syscall, long unsigned int work)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580872096,
      "name": "syscall_trace_enter",
      "external": true,
      "loc": "kernel/entry/common.c:28",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:__do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_emulation",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580872096,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490216568,
      "name": "syscall_trace_enter",
      "external": true,
      "loc": "arch/arm64/kernel/ptrace.c:1830",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490216568,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
int syscall_trace_enter(struct pt_regs * regs, int scno)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224424044,
      "name": "syscall_trace_enter",
      "external": true,
      "loc": "arch/arm/kernel/ptrace.c:917",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224424044,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
    }
  ]
}
```
</details>
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
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578860448,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "arch/x86/entry/common.c:69",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578860448,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578853504,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "arch/x86/entry/common.c:69",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578853504,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578860448,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "arch/x86/entry/common.c:69",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578860448,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
long int syscall_trace_enter(struct pt_regs * regs)
```

```json
{
  "name": "syscall_trace_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578860656,
      "name": "syscall_trace_enter",
      "external": false,
      "loc": "arch/x86/entry/common.c:69",
      "file": "arch/x86/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578860656,
      "name": "syscall_trace_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
long int syscall_trace_enter(struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
long int syscall_trace_enter(struct pt_regs * regs, long int syscall, long unsigned int work)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int scno</code>
</li>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int syscall_trace_enter(struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int syscall_trace_enter(struct pt_regs * regs)
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
