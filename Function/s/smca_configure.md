# Function: <code>smca_configure</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579150506,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:167",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init"
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
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579165417,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:169",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init"
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
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579176824,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:192",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init"
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
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579165672,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:193",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579178016,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:229",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579180416,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:231",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void smca_configure(unsigned int bank, unsigned int cpu)
```

```json
{
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:236",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196432,
      "name": "smca_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071579201355,
      "name": "smca_configure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void smca_configure(unsigned int bank, unsigned int cpu)
```

```json
{
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:236",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579192080,
      "name": "smca_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    },
    {
      "addr": 18446744071591254584,
      "name": "smca_configure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void smca_configure(unsigned int bank, unsigned int cpu)
```

```json
{
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:236",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579200928,
      "name": "smca_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    },
    {
      "addr": 18446744071591198329,
      "name": "smca_configure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void smca_configure(unsigned int bank, unsigned int cpu)
```

```json
{
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:249",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236848,
      "name": "smca_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
    },
    {
      "addr": 18446744071592065832,
      "name": "smca_configure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void smca_configure(unsigned int bank, unsigned int cpu)
```

```json
{
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:274",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288208,
      "name": "smca_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
    },
    {
      "addr": 18446744071593832260,
      "name": "smca_configure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void smca_configure(unsigned int bank, unsigned int cpu)
```

```json
{
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:274",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579353792,
      "name": "smca_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
    },
    {
      "addr": 18446744071595962075,
      "name": "smca_configure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void smca_configure(unsigned int bank, unsigned int cpu)
```

```json
{
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:274",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362784,
      "name": "smca_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
    },
    {
      "addr": 18446744071596479548,
      "name": "smca_configure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void smca_configure(unsigned int bank, unsigned int cpu)
```

```json
{
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:266",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579392752,
      "name": "smca_configure",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
    },
    {
      "addr": 18446744071597375408,
      "name": "smca_configure.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579180672,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:231",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579113313,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:231",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579180336,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:231",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
  "name": "smca_configure",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579185520,
      "name": "smca_configure",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:231",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void smca_configure(unsigned int bank, unsigned int cpu)
```
</details>
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
