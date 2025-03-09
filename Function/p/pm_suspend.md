# Function: <code>pm_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691488,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:528",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691488,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1015
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579710704,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:529",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710704,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 912
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738240,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:552",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738240,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 912
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579734368,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:575",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734368,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579767488,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:599",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579767488,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 939
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:604",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801945,
      "name": "pm_suspend.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 905
    },
    {
      "addr": 18446744071579801616,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579848569,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:610",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848569,
      "name": "pm_suspend.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 905
    },
    {
      "addr": 18446744071579848240,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579882645,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:615",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882645,
      "name": "pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
    },
    {
      "addr": 18446744071579882320,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579932897,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:605",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932897,
      "name": "pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
    },
    {
      "addr": 18446744071579932528,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579977582,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:605",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977582,
      "name": "pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071579976608,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591292927,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:605",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591292927,
      "name": "pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071579963360,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591235922,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:605",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591235922,
      "name": "pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071579966016,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580096796,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:603",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592123644,
      "name": "pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580096752,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580235013,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:604",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593893086,
      "name": "pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580234960,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580428544,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:611",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580428544,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580497840,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:611",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580497840,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580557728,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:611",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557728,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491143176,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:605",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store",
        "drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491143176,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1020
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225140000,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:605",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225140000,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1068
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284036752,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:605",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284036752,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_suspend",
      "external": false,
      "loc": "include/linux/suspend.h:344",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_suspend",
      "external": false,
      "loc": "include/linux/suspend.h:344",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579839950,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:605",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579839950,
      "name": "pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
    },
    {
      "addr": 18446744071579839568,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579893169,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:605",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893169,
      "name": "pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
    },
    {
      "addr": 18446744071579892800,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int pm_suspend(suspend_state_t state)
```

```json
{
  "name": "pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939153,
      "name": "pm_suspend",
      "external": true,
      "loc": "kernel/power/suspend.c:605",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939153,
      "name": "pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
    },
    {
      "addr": 18446744071579938784,
      "name": "pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pm_suspend(suspend_state_t state)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int pm_suspend(suspend_state_t state)
```
</details>
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
