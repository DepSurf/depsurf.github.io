# Function: <code>setup_local_APIC</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579188736,
      "name": "setup_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1214",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188736,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
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
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579189072,
      "name": "setup_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1248",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup",
        "arch/x86/kernel/apic/apic.c:apic_ap_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579189072,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 931
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
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579200592,
      "name": "setup_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1251",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup",
        "arch/x86/kernel/apic/apic.c:apic_ap_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579200592,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 931
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
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579198896,
      "name": "setup_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1334",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup",
        "arch/x86/kernel/apic/apic.c:apic_ap_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198896,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 861
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
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579214528,
      "name": "setup_local_APIC",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1417",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup",
        "arch/x86/kernel/apic/apic.c:apic_ap_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579214528,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 923
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
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1470",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup",
        "arch/x86/kernel/apic/apic.c:apic_ap_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222896,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 869
    },
    {
      "addr": 18446744071579228706,
      "name": "setup_local_APIC.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1476",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup",
        "arch/x86/kernel/apic/apic.c:apic_ap_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246576,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 870
    },
    {
      "addr": 18446744071579252402,
      "name": "setup_local_APIC.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1554",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260576,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 882
    },
    {
      "addr": 18446744071579266349,
      "name": "setup_local_APIC.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1598",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262224,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
    },
    {
      "addr": 18446744071579267997,
      "name": "setup_local_APIC.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1550",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579289408,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
    },
    {
      "addr": 18446744071579295541,
      "name": "setup_local_APIC.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1562",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579295472,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 629
    },
    {
      "addr": 18446744071591259308,
      "name": "setup_local_APIC.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1562",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298080,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    },
    {
      "addr": 18446744071591202580,
      "name": "setup_local_APIC.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1559",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345568,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    },
    {
      "addr": 18446744071592073576,
      "name": "setup_local_APIC.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1567",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407568,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    },
    {
      "addr": 18446744071593840209,
      "name": "setup_local_APIC.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488528,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1563",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488528,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1007
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
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579500720,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1565",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579500720,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1065
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
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1525",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531040,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
    },
    {
      "addr": 18446744071597379239,
      "name": "setup_local_APIC.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1598",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260928,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
    },
    {
      "addr": 18446744071579266701,
      "name": "setup_local_APIC.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1598",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196288,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
    },
    {
      "addr": 18446744071579202047,
      "name": "setup_local_APIC.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1598",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262128,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
    },
    {
      "addr": 18446744071579267901,
      "name": "setup_local_APIC.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void setup_local_APIC()
```

```json
{
  "name": "setup_local_APIC",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_local_APIC",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:1598",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_ap_setup",
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267728,
      "name": "setup_local_APIC",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
    },
    {
      "addr": 18446744071579273501,
      "name": "setup_local_APIC.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void setup_local_APIC()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void setup_local_APIC()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void setup_local_APIC()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void setup_local_APIC()
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
