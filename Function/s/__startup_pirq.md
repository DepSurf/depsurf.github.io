# Function: <code>__startup_pirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583859936,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:504",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:xen_irq_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859936,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584190432,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:515",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:enable_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584190432,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584371888,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:514",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:enable_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584371888,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584453472,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:506",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584453472,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864128,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:506",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864128,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:506",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585095200,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071585101228,
      "name": "__startup_pirq.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:506",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585205984,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071585212005,
      "name": "__startup_pirq.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:507",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585418336,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071585424410,
      "name": "__startup_pirq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:507",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585559056,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071585564982,
      "name": "__startup_pirq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:521",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:restore_pirqs",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586279312,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071586286121,
      "name": "__startup_pirq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:841",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:restore_pirqs",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586399712,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    },
    {
      "addr": 18446744071591448378,
      "name": "__startup_pirq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:872",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586283104,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    },
    {
      "addr": 18446744071591390148,
      "name": "__startup_pirq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:872",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797488,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    },
    {
      "addr": 18446744071592433768,
      "name": "__startup_pirq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:872",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588078864,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
    },
    {
      "addr": 18446744071594301865,
      "name": "__startup_pirq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589460656,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:874",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589460656,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589760576,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:866",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589760576,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
unsigned int __startup_pirq(struct irq_info * info)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590092624,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:861",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590092624,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498220856,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:507",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498220856,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    }
  ]
}
```
</details>
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:511",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_restore_pirqs",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585320768,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071585326950,
      "name": "__startup_pirq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:507",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585509456,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071585515382,
      "name": "__startup_pirq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
unsigned int __startup_pirq(unsigned int irq)
```

```json
{
  "name": "__startup_pirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__startup_pirq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:507",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585617472,
      "name": "__startup_pirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071585623398,
      "name": "__startup_pirq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_info * info</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int irq</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int __startup_pirq(unsigned int irq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int __startup_pirq(unsigned int irq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int __startup_pirq(unsigned int irq)
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
unsigned int __startup_pirq(unsigned int irq)
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
