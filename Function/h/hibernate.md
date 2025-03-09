# Function: <code>hibernate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579696752,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:648",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579696752,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579715904,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:681",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715904,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579743472,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:683",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743472,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579739616,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:678",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579739616,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772816,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:678",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772816,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:685",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807309,
      "name": "hibernate.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    },
    {
      "addr": 18446744071579806464,
      "name": "hibernate",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:687",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853952,
      "name": "hibernate.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    },
    {
      "addr": 18446744071579853104,
      "name": "hibernate",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:694",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888166,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
    },
    {
      "addr": 18446744071579887312,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:695",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938418,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
    },
    {
      "addr": 18446744071579937568,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:707",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982671,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071579981632,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:707",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591293907,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071579967632,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:707",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591236746,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071579970224,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:710",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592124403,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
    },
    {
      "addr": 18446744071580101360,
      "name": "hibernate",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:713",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593894387,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
    },
    {
      "addr": 18446744071580240496,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:717",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595984200,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071580435840,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:718",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596502345,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580504848,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 961
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:724",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597400031,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580564720,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 954
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "hibernate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": false,
      "loc": "include/linux/suspend.h:462",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225146052,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:695",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225146052,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "hibernate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": false,
      "loc": "include/linux/suspend.h:462",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "hibernate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": false,
      "loc": "include/linux/suspend.h:462",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:695",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906258,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    },
    {
      "addr": 18446744071579905408,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:695",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845426,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
    },
    {
      "addr": 18446744071579844576,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:695",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898690,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
    },
    {
      "addr": 18446744071579897840,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int hibernate()
```

```json
{
  "name": "hibernate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernate",
      "external": true,
      "loc": "kernel/power/hibernate.c:695",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/main.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944722,
      "name": "hibernate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
    },
    {
      "addr": 18446744071579943872,
      "name": "hibernate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int hibernate()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int hibernate()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int hibernate()
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
