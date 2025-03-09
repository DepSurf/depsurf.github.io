# Function: <code>disable_local_APIC</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579188144,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1039",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188144,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579188448,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1071",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188448,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579199968,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1074",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579199968,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579198672,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1157",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_suspend",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/apic/apic.c:lapic_suspend",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198192,
      "name": "disable_local_APIC.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579198736,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579214317,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1144",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_suspend",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/apic/apic.c:lapic_suspend",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213792,
      "name": "disable_local_APIC.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579214368,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579226736,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1148",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226736,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579250432,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1154",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250432,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579264416,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1229",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264416,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579266699,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1261",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266592,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579294363,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1213",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294256,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579300379,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1222",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300272,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579303243,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1222",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579303136,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579350907,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1219",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350800,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579412729,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1228",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412608,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579494713,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1224",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494576,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506969,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1226",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smp.c:native_stop_other_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506832,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535200,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1192",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smp.c:native_stop_other_cpus",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535200,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579265403,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1261",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265296,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579200861,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1261",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579200768,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579266603,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1261",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266496,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void disable_local_APIC()
```

```json
{
  "name": "disable_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579272203,
      "name": "disable_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1261",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/crash.c:kdump_nmi_shootdown_cpus",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272096,
      "name": "disable_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void disable_local_APIC()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void disable_local_APIC()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void disable_local_APIC()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void disable_local_APIC()
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
