# Function: <code>__x2apic_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579185520,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1450",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:x2apic_setup",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185520,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579184672,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1486",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184672,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579196176,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1488",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196176,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579194912,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1571",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194912,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211696,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1656",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211696,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1669",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224672,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579228914,
      "name": "__x2apic_enable.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1675",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248368,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579252611,
      "name": "__x2apic_enable.cold.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1753",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262336,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579266624,
      "name": "__x2apic_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1810",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263920,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579268277,
      "name": "__x2apic_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1762",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290928,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071579296130,
      "name": "__x2apic_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1774",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296976,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071591259868,
      "name": "__x2apic_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1775",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299776,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071591202966,
      "name": "__x2apic_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592073988,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1772",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347376,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071592073968,
      "name": "__x2apic_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1780",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408848,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071593840503,
      "name": "__x2apic_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1791",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490528,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071595965485,
      "name": "__x2apic_enable.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579502890,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1793",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502784,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071596483139,
      "name": "__x2apic_enable.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579533418,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1754",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533312,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071597379279,
      "name": "__x2apic_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1810",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262624,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579266981,
      "name": "__x2apic_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1810",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198000,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071579202402,
      "name": "__x2apic_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1810",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263824,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579268181,
      "name": "__x2apic_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __x2apic_enable()
```

```json
{
  "name": "__x2apic_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x2apic_enable",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1810",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269424,
      "name": "__x2apic_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579273781,
      "name": "__x2apic_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __x2apic_enable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __x2apic_enable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __x2apic_enable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __x2apic_enable()
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
