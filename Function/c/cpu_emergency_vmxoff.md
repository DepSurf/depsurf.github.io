# Function: <code>cpu_emergency_vmxoff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579173708,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227693,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
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
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579174092,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227944,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579184444,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240357,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579183180,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185445,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236389,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579198810,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201112,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252824,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579210621,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213007,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264265,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579234349,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236687,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288857,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:64",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579247677,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250110,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305241,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579249837,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251838,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309337,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579274573,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275905,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338275,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579281821,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:69",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283105,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:69",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338280,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:69",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579284604,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:75",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286673,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:75",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342056,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:75",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579328364,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:75",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330417,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:75",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399496,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:75",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579389052,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:75",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390800,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:75",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465356,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:75",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpu_emergency_vmxoff()
```

```json
{
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579467361,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:75",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:crash_nmi_callback"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466912,
      "name": "cpu_emergency_vmxoff",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpu_emergency_vmxoff()
```

```json
{
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579479809,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:75",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:crash_nmi_callback"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479360,
      "name": "cpu_emergency_vmxoff",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579248541,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250542,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305241,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579184031,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185815,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239715,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579249741,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251742,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305241,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
  "name": "cpu_emergency_vmxoff",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579255309,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257310,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313459,
      "name": "cpu_emergency_vmxoff",
      "external": false,
      "loc": "arch/x86/include/asm/virtext.h:62",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void cpu_emergency_vmxoff()
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void cpu_emergency_vmxoff()
```
</details>
</li>
</ul>
