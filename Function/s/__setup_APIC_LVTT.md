# Function: <code>__setup_APIC_LVTT</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579185072,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:320",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185072,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579185600,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:328",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185600,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579197104,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:329",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197104,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579194688,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:331",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194688,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579210288,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:322",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210288,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:323",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223936,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071579228866,
      "name": "__setup_APIC_LVTT.cold.22",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579247688,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:329",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247616,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071579252563,
      "name": "__setup_APIC_LVTT.cold.23",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579261704,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:330",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261632,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071579266510,
      "name": "__setup_APIC_LVTT.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579263288,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:330",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263216,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071579268163,
      "name": "__setup_APIC_LVTT.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579288528,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:330",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288528,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579294560,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:336",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294560,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579297232,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:336",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297232,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579344672,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:333",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344672,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579406688,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:336",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406688,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579487856,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:337",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487856,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579499920,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:340",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499920,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621707645,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:307",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic"
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
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579261992,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:330",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261920,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071579266867,
      "name": "__setup_APIC_LVTT.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579197352,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:330",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197280,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071579202213,
      "name": "__setup_APIC_LVTT.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579263192,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:330",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263120,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071579268067,
      "name": "__setup_APIC_LVTT.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```

```json
{
  "name": "__setup_APIC_LVTT",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579268792,
      "name": "__setup_APIC_LVTT",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:330",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268720,
      "name": "__setup_APIC_LVTT",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071579273667,
      "name": "__setup_APIC_LVTT.cold",
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
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
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen)
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
