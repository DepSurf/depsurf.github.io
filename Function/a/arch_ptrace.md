# Function: <code>arch_ptrace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579093856,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:813",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579093856,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579093200,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:766",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579093200,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579091280,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:766",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579091280,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 803
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579083152,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:767",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579083152,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 766
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579093920,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:767",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579093920,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579099440,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:767",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579099440,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579105040,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:758",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579105040,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579114976,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:730",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579114976,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579116896,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:730",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579116896,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579131168,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:745",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579131168,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 980
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579129760,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:708",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579129760,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1050
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579136736,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:711",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136736,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 713
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163392,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:711",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163392,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 774
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579208368,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:710",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208368,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 911
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579263872,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:729",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263872,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 911
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579270000,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:729",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270000,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 851
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579299824,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:730",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:ia32_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299824,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 851
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490216488,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/arm64/kernel/ptrace.c:1797",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__arm64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490216488,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224422524,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/arm/kernel/ptrace.c:784",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__se_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224422524,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1520
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282264624,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/powerpc/kernel/ptrace.c:2983",
      "file": "arch/powerpc/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace",
        "kernel/ptrace.c:__se_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282264624,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2012
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271344324,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/riscv/kernel/ptrace.c:133",
      "file": "arch/riscv/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__se_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271344324,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579117280,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:730",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579117280,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049376,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:730",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049376,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579116832,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:730",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579116832,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
long int arch_ptrace(struct task_struct * child, long int request, long unsigned int addr, long unsigned int data)
```

```json
{
  "name": "arch_ptrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121920,
      "name": "arch_ptrace",
      "external": true,
      "loc": "arch/x86/kernel/ptrace.c:730",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121920,
      "name": "arch_ptrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
