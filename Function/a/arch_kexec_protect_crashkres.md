# Function: <code>arch_kexec_protect_crashkres</code>

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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579223312,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:577",
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
      "addr": 18446744071579223312,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579235472,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:578",
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
      "addr": 18446744071579235472,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579233120,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:596",
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
      "addr": 18446744071579233120,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579248800,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:599",
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
      "addr": 18446744071579248800,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579260928,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:549",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071579260928,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579284688,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:549",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071579284688,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579299776,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:647",
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
      "addr": 18446744071579299776,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305328,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:647",
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
      "addr": 18446744071579305328,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334848,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:580",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334848,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579336432,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:580",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579336432,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579339136,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:580",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339136,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579394512,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:551",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394512,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579461088,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:560",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461088,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550464,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:560",
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
      "addr": 18446744071579550464,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565616,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:549",
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
      "addr": 18446744071579565616,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593152,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:546",
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
      "addr": 18446744071579593152,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490328200,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/arm64/kernel/machine_kexec.c:275",
      "file": "arch/arm64/kernel/machine_kexec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490328200,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225488876,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "kernel/kexec_core.c:1211",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225488876,
      "name": "arch_kexec_protect_crashkres",
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284468192,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "kernel/kexec_core.c:1211",
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
      "addr": 13835058055284468192,
      "name": "arch_kexec_protect_crashkres",
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579301136,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:647",
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
      "addr": 18446744071579301136,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236576,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:647",
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
      "addr": 18446744071579236576,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302336,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:647",
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
      "addr": 18446744071579302336,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void arch_kexec_protect_crashkres()
```

```json
{
  "name": "arch_kexec_protect_crashkres",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579311168,
      "name": "arch_kexec_protect_crashkres",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:647",
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
      "addr": 18446744071579311168,
      "name": "arch_kexec_protect_crashkres",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void arch_kexec_protect_crashkres()
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
void arch_kexec_protect_crashkres()
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
