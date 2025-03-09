# Function: <code>load_direct_gdt</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579098163,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:475",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:switch_to_new_gdt"
      ],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579097360,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108560,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:514",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108560,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579114816,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:524",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579114816,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579120480,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:524",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579120480,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579129904,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:588",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579129904,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579131776,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:588",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579131776,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579148336,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:593",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148336,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579145424,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:611",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579145424,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579151664,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:609",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579151664,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579180448,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:612",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180448,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579227488,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:720",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227488,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579286048,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:712",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:switch_gdt_and_percpu_base",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286048,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579292624,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:701",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:switch_gdt_and_percpu_base",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292624,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621633227,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:698",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:switch_gdt_and_percpu_base"
      ],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321680,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579132160,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:588",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132160,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579068020,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:588",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063200,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579131712,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:588",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579131712,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void load_direct_gdt(int cpu)
```

```json
{
  "name": "load_direct_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579136832,
      "name": "load_direct_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:588",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136832,
      "name": "load_direct_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void load_direct_gdt(int cpu)
```
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
void load_direct_gdt(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void load_direct_gdt(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void load_direct_gdt(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void load_direct_gdt(int cpu)
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
