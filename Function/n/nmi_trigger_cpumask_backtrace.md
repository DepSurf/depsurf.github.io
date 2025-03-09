# Function: <code>nmi_trigger_cpumask_backtrace</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583367200,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:34",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367200,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588216256,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:35",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216256,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588766208,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588766208,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589145269,
      "name": "nmi_trigger_cpumask_backtrace.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071589144944,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589380405,
      "name": "nmi_trigger_cpumask_backtrace.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071589380080,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589837453,
      "name": "nmi_trigger_cpumask_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071589837136,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590063597,
      "name": "nmi_trigger_cpumask_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071590063280,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585060494,
      "name": "nmi_trigger_cpumask_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585060176,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591382138,
      "name": "nmi_trigger_cpumask_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585209616,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591324573,
      "name": "nmi_trigger_cpumask_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585092592,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592342708,
      "name": "nmi_trigger_cpumask_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585540192,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594204270,
      "name": "nmi_trigger_cpumask_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071586694816,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595856240,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595856240,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, int exclude_cpu, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596373120,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596373120,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, int exclude_cpu, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597266480,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597266480,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236459660,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236459660,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297691824,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/stacktrace.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297691824,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589665853,
      "name": "nmi_trigger_cpumask_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071589665536,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589391677,
      "name": "nmi_trigger_cpumask_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071589391360,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590109229,
      "name": "nmi_trigger_cpumask_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071590108912,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```

```json
{
  "name": "nmi_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_trigger_cpumask_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:36",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590159563,
      "name": "nmi_trigger_cpumask_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071590159216,
      "name": "nmi_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int exclude_cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>bool exclude_self</code>
</li>
</ul>
</details>
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
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
```
</details>
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
void nmi_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self, void (*)(cpumask_t *) raise)
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
