# Function: <code>lapic_timer_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579184864,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:472",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184864,
      "name": "lapic_timer_shutdown.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579184944,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579185511,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:480",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185328,
      "name": "lapic_timer_shutdown.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579185408,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579197015,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:481",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196832,
      "name": "lapic_timer_shutdown.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579196912,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579194256,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:483",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194256,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579210016,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:474",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210016,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589340508,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:475",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223776,
      "name": "lapic_timer_shutdown.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579223872,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591437828,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:481",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247456,
      "name": "lapic_timer_shutdown.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579247552,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591438420,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:482",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261472,
      "name": "lapic_timer_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579261568,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591438468,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:482",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263056,
      "name": "lapic_timer_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579263152,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579296109,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:480",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290048,
      "name": "lapic_timer_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579290144,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591259846,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:489",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296112,
      "name": "lapic_timer_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579296208,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591202944,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:489",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297872,
      "name": "lapic_timer_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579297968,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592073946,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:486",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345360,
      "name": "lapic_timer_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579345456,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593840483,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:495",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406944,
      "name": "lapic_timer_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579407040,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579489921,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:496",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488128,
      "name": "lapic_timer_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579488240,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579502177,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:498",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579500192,
      "name": "lapic_timer_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579500304,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579533728,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:465",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533120,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591438436,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:482",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261760,
      "name": "lapic_timer_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579261856,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591438100,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:482",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197120,
      "name": "lapic_timer_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579197216,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591438292,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:482",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262960,
      "name": "lapic_timer_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579263056,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "lapic_timer_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591438930,
      "name": "lapic_timer_shutdown",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:482",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268560,
      "name": "lapic_timer_shutdown.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579268656,
      "name": "lapic_timer_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int lapic_timer_shutdown(struct clock_event_device * evt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int lapic_timer_shutdown(struct clock_event_device * evt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int lapic_timer_shutdown(struct clock_event_device * evt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int lapic_timer_shutdown(struct clock_event_device * evt)
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
