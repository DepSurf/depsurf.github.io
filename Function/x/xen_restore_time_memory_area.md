# Function: <code>xen_restore_time_memory_area</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578958816,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:394",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958816,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:394",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578961416,
      "name": "xen_restore_time_memory_area.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578961312,
      "name": "xen_restore_time_memory_area",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:402",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578960220,
      "name": "xen_restore_time_memory_area.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578960080,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:402",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967228,
      "name": "xen_restore_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578966848,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:402",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969654,
      "name": "xen_restore_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578969312,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:409",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578979249,
      "name": "xen_restore_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578978704,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:410",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591241886,
      "name": "xen_restore_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578981328,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:405",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591184958,
      "name": "xen_restore_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071578990448,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:405",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592046783,
      "name": "xen_restore_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579007504,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:405",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593813202,
      "name": "xen_restore_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579024896,
      "name": "xen_restore_time_memory_area",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579053280,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:405",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053280,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579053184,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:413",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053184,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078512,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:413",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078512,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:402",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969670,
      "name": "xen_restore_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578969328,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:402",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969590,
      "name": "xen_restore_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578969248,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void xen_restore_time_memory_area()
```

```json
{
  "name": "xen_restore_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_restore_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:402",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970186,
      "name": "xen_restore_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578969856,
      "name": "xen_restore_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void xen_restore_time_memory_area()
```
</details>
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
void xen_restore_time_memory_area()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_restore_time_memory_area()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_restore_time_memory_area()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_restore_time_memory_area()
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
void xen_restore_time_memory_area()
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
