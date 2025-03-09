# Function: <code>xen_enable_sysenter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578965728,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:988",
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
      "addr": 18446744071578965728,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578962576,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:975",
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
      "addr": 18446744071578962576,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578964400,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:975",
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
      "addr": 18446744071578964400,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578958832,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:967",
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
      "addr": 18446744071578958832,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578962144,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:964",
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
      "addr": 18446744071578962144,
      "name": "xen_enable_sysenter.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071578962240,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602784339,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:964",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup"
      ],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964736,
      "name": "xen_enable_sysenter.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071578964832,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604578312,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:935",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup"
      ],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578962832,
      "name": "xen_enable_sysenter.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071578962928,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604673477,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:948",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup"
      ],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969808,
      "name": "xen_enable_sysenter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071578969904,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604685957,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:948",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup"
      ],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972240,
      "name": "xen_enable_sysenter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071578972336,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578981984,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:949",
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
      "addr": 18446744071578981984,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578983856,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:915",
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
      "addr": 18446744071578983856,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578992960,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:915",
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
      "addr": 18446744071578992960,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579010336,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:915",
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
      "addr": 18446744071579010336,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579028368,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:911",
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
      "addr": 18446744071579028368,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579057568,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:912",
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
      "addr": 18446744071579057568,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579057456,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:922",
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
      "addr": 18446744071579057456,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082800,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:928",
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
      "addr": 18446744071579082800,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604612253,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:948",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup"
      ],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972592,
      "name": "xen_enable_sysenter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071578972688,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604690053,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:948",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup"
      ],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972176,
      "name": "xen_enable_sysenter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071578972272,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void xen_enable_sysenter()
```

```json
{
  "name": "xen_enable_sysenter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604690009,
      "name": "xen_enable_sysenter",
      "external": true,
      "loc": "arch/x86/xen/setup.c:948",
      "file": "arch/x86/xen/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup"
      ],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_pvmmu_arch_setup",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972768,
      "name": "xen_enable_sysenter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071578972864,
      "name": "xen_enable_sysenter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void xen_enable_sysenter()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_enable_sysenter()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_enable_sysenter()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_enable_sysenter()
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
void xen_enable_sysenter()
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
