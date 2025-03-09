# Function: <code>crash_setup_regs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579949423,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:92",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579980698,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:92",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580011194,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:92",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void crash_setup_regs(struct pt_regs * newregs, struct pt_regs * oldregs)
```

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014208,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:92",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:__crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014208,
      "name": "crash_setup_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void crash_setup_regs(struct pt_regs * newregs, struct pt_regs * oldregs)
```

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580061136,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:93",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:__crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061136,
      "name": "crash_setup_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580117359,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:93",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580165359,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:94",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580211471,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:78",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580259871,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:78",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580327583,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:74",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580313055,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:74",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580316543,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:74",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580470255,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:74",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580664131,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:74",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void crash_setup_regs(struct pt_regs * newregs, struct pt_regs * oldregs)
```

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580934160,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:74",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:__crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580934160,
      "name": "crash_setup_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void crash_setup_regs(struct pt_regs * newregs, struct pt_regs * oldregs)
```

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581020880,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:74",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:__crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020880,
      "name": "crash_setup_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void crash_setup_regs(struct pt_regs * newregs, struct pt_regs * oldregs)
```

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581118976,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:74",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:__crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118976,
      "name": "crash_setup_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491505876,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/arm64/include/asm/kexec.h:37",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224457412,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/arm/include/asm/kexec.h:36",
      "file": "arch/arm/kernel/machine_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core"
      ],
      "caller_func": []
    },
    {
      "addr": 3225487692,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/arm/include/asm/kexec.h:36",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284466504,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/powerpc/include/asm/kexec.h:63",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580228671,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:78",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580176159,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:78",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580220143,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:78",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crash_setup_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580272975,
      "name": "crash_setup_regs",
      "external": false,
      "loc": "arch/x86/include/asm/kexec.h:78",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:__crash_kexec"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void crash_setup_regs(struct pt_regs * newregs, struct pt_regs * oldregs)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void crash_setup_regs(struct pt_regs * newregs, struct pt_regs * oldregs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void crash_setup_regs(struct pt_regs * newregs, struct pt_regs * oldregs)
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
