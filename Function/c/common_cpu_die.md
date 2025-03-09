# Function: <code>common_cpu_die</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579182816,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1509",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579182816,
      "name": "common_cpu_die",
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
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579183088,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1536",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183088,
      "name": "common_cpu_die",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579193600,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1564",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579193600,
      "name": "common_cpu_die",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579191840,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1570",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191840,
      "name": "common_cpu_die",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579207648,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1483",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207648,
      "name": "common_cpu_die",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1539",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220150,
      "name": "common_cpu_die.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071579219056,
      "name": "common_cpu_die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1540",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243840,
      "name": "common_cpu_die.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071579242736,
      "name": "common_cpu_die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1605",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257864,
      "name": "common_cpu_die.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579256720,
      "name": "common_cpu_die",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1605",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259509,
      "name": "common_cpu_die.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579258384,
      "name": "common_cpu_die",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579284821,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1632",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286374,
      "name": "common_cpu_die.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579284752,
      "name": "common_cpu_die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579292115,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1626",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591258835,
      "name": "common_cpu_die.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579292032,
      "name": "common_cpu_die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579294835,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1627",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591201965,
      "name": "common_cpu_die.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579294752,
      "name": "common_cpu_die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579341955,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1634",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592072787,
      "name": "common_cpu_die.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579341872,
      "name": "common_cpu_die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579403009,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1699",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593839342,
      "name": "common_cpu_die.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579402928,
      "name": "common_cpu_die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579483489,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1699",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483360,
      "name": "common_cpu_die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1605",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258213,
      "name": "common_cpu_die.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579257088,
      "name": "common_cpu_die",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1605",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579193402,
      "name": "common_cpu_die.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579192304,
      "name": "common_cpu_die",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1605",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259413,
      "name": "common_cpu_die.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579258288,
      "name": "common_cpu_die",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int common_cpu_die(unsigned int cpu)
```

```json
{
  "name": "common_cpu_die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "common_cpu_die",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1605",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/smpboot.c:native_cpu_die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265013,
      "name": "common_cpu_die.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579263888,
      "name": "common_cpu_die",
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int common_cpu_die(unsigned int cpu)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int common_cpu_die(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int common_cpu_die(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int common_cpu_die(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int common_cpu_die(unsigned int cpu)
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
