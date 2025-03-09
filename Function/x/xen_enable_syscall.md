# Function: <code>xen_enable_syscall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578965856,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:1007",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578965856,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578962704,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:994",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578962704,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578964528,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:994",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964528,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578958944,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:986",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958944,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578962272,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:983",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578962272,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:983",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578965090,
      "name": "xen_enable_syscall.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578964864,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578963053,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:954",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578963186,
      "name": "xen_enable_syscall.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578962960,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578970012,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:967",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970162,
      "name": "xen_enable_syscall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578969936,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578972444,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:967",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972594,
      "name": "xen_enable_syscall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578972368,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578982172,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:968",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578982322,
      "name": "xen_enable_syscall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578982096,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578984044,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:930",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591242272,
      "name": "xen_enable_syscall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578983968,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578993148,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:930",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591185342,
      "name": "xen_enable_syscall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578993072,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579010524,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:930",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592047267,
      "name": "xen_enable_syscall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579010448,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579028573,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:926",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593813871,
      "name": "xen_enable_syscall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579028496,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579057712,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:919",
      "file": "arch/x86/xen/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057712,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579057600,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:929",
      "file": "arch/x86/xen/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057600,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082944,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:935",
      "file": "arch/x86/xen/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082944,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578972796,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:967",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972946,
      "name": "xen_enable_syscall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578972720,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578972380,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:967",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972530,
      "name": "xen_enable_syscall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578972304,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xen_enable_syscall()
```

```json
{
  "name": "xen_enable_syscall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578972972,
      "name": "xen_enable_syscall",
      "external": true,
      "loc": "arch/x86/xen/setup.c:967",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578973122,
      "name": "xen_enable_syscall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578972896,
      "name": "xen_enable_syscall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void xen_enable_syscall()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_enable_syscall()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_enable_syscall()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_enable_syscall()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void xen_enable_syscall()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
