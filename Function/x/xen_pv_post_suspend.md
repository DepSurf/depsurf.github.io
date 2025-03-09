# Function: <code>xen_pv_post_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578993148,
      "name": "xen_pv_post_suspend",
      "external": false,
      "loc": "arch/x86/xen/suspend.c:49",
      "file": "arch/x86/xen/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578989756,
      "name": "xen_pv_post_suspend",
      "external": false,
      "loc": "arch/x86/xen/suspend.c:49",
      "file": "arch/x86/xen/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578991630,
      "name": "xen_pv_post_suspend",
      "external": false,
      "loc": "arch/x86/xen/suspend.c:49",
      "file": "arch/x86/xen/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578964048,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:26",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964048,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578967328,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967328,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970376,
      "name": "xen_pv_post_suspend.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071578969952,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578968503,
      "name": "xen_pv_post_suspend.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071578968016,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578975547,
      "name": "xen_pv_post_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071578975072,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977947,
      "name": "xen_pv_post_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071578977472,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578987777,
      "name": "xen_pv_post_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071578987296,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591242567,
      "name": "xen_pv_post_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071578988784,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591185635,
      "name": "xen_pv_post_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071578997760,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592047763,
      "name": "xen_pv_post_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579015440,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593814255,
      "name": "xen_pv_post_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579034048,
      "name": "xen_pv_post_suspend",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579063776,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063776,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579063648,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063648,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088736,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088736,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978299,
      "name": "xen_pv_post_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071578977824,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977883,
      "name": "xen_pv_post_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071578977408,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
void xen_pv_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_pv_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pv_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:27",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978475,
      "name": "xen_pv_post_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071578978000,
      "name": "xen_pv_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled)
```
</details>
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
void xen_pv_post_suspend(int suspend_cancelled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled)
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
void xen_pv_post_suspend(int suspend_cancelled)
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
