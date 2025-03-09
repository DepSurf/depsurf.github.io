# Function: <code>hv_send_ipi_mask_allbutself</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579024352,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:203",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579024352,
      "name": "hv_send_ipi_mask_allbutself.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579025408,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071579025666,
      "name": "hv_send_ipi_mask_allbutself.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579028400,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:210",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579028400,
      "name": "hv_send_ipi_mask_allbutself.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579029504,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071579029762,
      "name": "hv_send_ipi_mask_allbutself.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579035952,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:215",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579035952,
      "name": "hv_send_ipi_mask_allbutself.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579037152,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071579037412,
      "name": "hv_send_ipi_mask_allbutself.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579038272,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:215",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038272,
      "name": "hv_send_ipi_mask_allbutself.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579039472,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071579039812,
      "name": "hv_send_ipi_mask_allbutself.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579047840,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:225",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047840,
      "name": "hv_send_ipi_mask_allbutself.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579048800,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071579049844,
      "name": "hv_send_ipi_mask_allbutself.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579051168,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:225",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579051168,
      "name": "hv_send_ipi_mask_allbutself.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579052096,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071591243667,
      "name": "hv_send_ipi_mask_allbutself.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579056352,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:229",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056352,
      "name": "hv_send_ipi_mask_allbutself.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579057312,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071591187311,
      "name": "hv_send_ipi_mask_allbutself.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579078933,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:255",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself",
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078800,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579107125,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:255",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself",
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106976,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579143893,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:255",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself",
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143712,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579144501,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:257",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself",
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579144320,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579174293,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:266",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself",
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579173600,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579038624,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:215",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038624,
      "name": "hv_send_ipi_mask_allbutself.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579039824,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071579040164,
      "name": "hv_send_ipi_mask_allbutself.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578971168,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:215",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578971168,
      "name": "hv_send_ipi_mask_allbutself.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071578972256,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071578973044,
      "name": "hv_send_ipi_mask_allbutself.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579038208,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:215",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038208,
      "name": "hv_send_ipi_mask_allbutself.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579039408,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071579039748,
      "name": "hv_send_ipi_mask_allbutself.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "hv_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579041856,
      "name": "hv_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/hyperv/hv_apic.c:215",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041856,
      "name": "hv_send_ipi_mask_allbutself.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579043072,
      "name": "hv_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071579043412,
      "name": "hv_send_ipi_mask_allbutself.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```
</details>
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
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
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
