# Function: <code>arch_kexec_unprotect_crashkres</code>

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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579223344,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:582",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223344,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579235504,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:583",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235504,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579233152,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:601",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579233152,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579248832,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:604",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248832,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579260960,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:554",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260960,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579284720,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:554",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284720,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579299808,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:652",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299808,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305360,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:652",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305360,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334880,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:585",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334880,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579336464,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:585",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579336464,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579339168,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:585",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339168,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394544,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:556",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394544,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461120,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:565",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461120,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550512,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:565",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550512,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565664,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:554",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565664,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593200,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:551",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:crash_handle_hotplug_event",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593200,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490328336,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/arm64/kernel/machine_kexec.c:287",
      "file": "arch/arm64/kernel/machine_kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490328336,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "kernel/kexec_core.c:1214",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225488900,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284468208,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "kernel/kexec_core.c:1214",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__se_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284468208,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 12
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579301168,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:652",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301168,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236608,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:652",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236608,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302368,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:652",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302368,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
```

```json
{
  "name": "arch_kexec_unprotect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579311200,
      "name": "arch_kexec_unprotect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:652",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311200,
      "name": "arch_kexec_unprotect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void arch_kexec_unprotect_crashkres()
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void arch_kexec_unprotect_crashkres()
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
