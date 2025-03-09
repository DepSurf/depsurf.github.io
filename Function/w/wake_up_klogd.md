# Function: <code>wake_up_klogd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579728877,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2741",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737152,
      "name": "wake_up_klogd",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579749537,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2883",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock"
      ],
      "caller_func": [
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758080,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579775979,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2715",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock"
      ],
      "caller_func": [
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784032,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579773438,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2713",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock"
      ],
      "caller_func": [
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780688,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579805850,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2707",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock"
      ],
      "caller_func": [
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814160,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846352,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2880",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846352,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893344,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2892",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893344,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579928096,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2957",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579928096,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579978240,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2967",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579978240,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580025534,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:3029",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026784,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580004960,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:3108",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006208,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580006496,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:3172",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007936,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580139055,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:3231",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592133844,
      "name": "wake_up_klogd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580139024,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580282089,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:3497",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593904928,
      "name": "wake_up_klogd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580283744,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580490825,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:3760",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595985817,
      "name": "wake_up_klogd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580493120,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580562665,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:3801",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596504113,
      "name": "wake_up_klogd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580564960,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580623482,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:3912",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597401820,
      "name": "wake_up_klogd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580628112,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491162056,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2967",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491162056,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225189400,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2967",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225189400,
      "name": "wake_up_klogd",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284061120,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2967",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284061120,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271716740,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2967",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271716740,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579946976,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2967",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946976,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884960,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2967",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884960,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579938512,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2967",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938512,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void wake_up_klogd()
```

```json
{
  "name": "wake_up_klogd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984736,
      "name": "wake_up_klogd",
      "external": true,
      "loc": "kernel/printk/printk.c:2967",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "lib/bust_spinlocks.c:bust_spinlocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984736,
      "name": "wake_up_klogd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
