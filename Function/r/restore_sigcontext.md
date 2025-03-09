# Function: <code>restore_sigcontext</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579034224,
      "name": "restore_sigcontext",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:64",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579034224,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579029504,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:93",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029504,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579029152,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:94",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029152,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579021568,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:95",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021568,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579024944,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:96",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579024944,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579029760,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:97",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029760,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579034448,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:97",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579034448,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579041968,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:97",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041968,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579044336,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:97",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044336,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * usc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579056640,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:81",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056640,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * usc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579059312,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:82",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579059312,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * usc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579066368,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:82",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066368,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * usc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579087488,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:82",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579087488,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
bool restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * usc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579113856,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:83",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579113856,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
bool restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * usc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579154576,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal_64.c:50",
      "file": "arch/x86/kernel/signal_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579154576,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
bool restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * usc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579156768,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal_64.c:50",
      "file": "arch/x86/kernel/signal_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156768,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
bool restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * usc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579186080,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal_64.c:50",
      "file": "arch/x86/kernel/signal_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579186080,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282368032,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/powerpc/kernel/signal_64.c:321",
      "file": "arch/powerpc/kernel/signal_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn",
        "arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282368032,
      "name": "restore_sigcontext.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1920
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271345892,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/riscv/kernel/signal.c:81",
      "file": "arch/riscv/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/signal.c:sys_rt_sigreturn"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579044688,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:97",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044688,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578977664,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:97",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977664,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579044272,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:97",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044272,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```

```json
{
  "name": "restore_sigcontext",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579048000,
      "name": "restore_sigcontext",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:97",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048000,
      "name": "restore_sigcontext",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
<code>long unsigned int uc_flags</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sigcontext_64 * usc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sigcontext_64 * sc</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int restore_sigcontext(struct pt_regs * regs, struct sigcontext_64 * sc, long unsigned int uc_flags)
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
