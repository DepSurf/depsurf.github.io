# Function: <code>xen_save_time_memory_area</code>

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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578958704,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:376",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958704,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:376",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578961397,
      "name": "xen_save_time_memory_area.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578961200,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:382",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578960201,
      "name": "xen_save_time_memory_area.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578959936,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:382",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967209,
      "name": "xen_save_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578966704,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:382",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969635,
      "name": "xen_save_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578969168,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:389",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578979230,
      "name": "xen_save_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578978560,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:390",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591241867,
      "name": "xen_save_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578981184,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:385",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591184941,
      "name": "xen_save_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071578990304,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:385",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592046766,
      "name": "xen_save_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579007360,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:385",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593813185,
      "name": "xen_save_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579024704,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579053056,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:385",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053056,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579052960,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:393",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052960,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078288,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:393",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078288,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:382",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969651,
      "name": "xen_save_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578969184,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:382",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969571,
      "name": "xen_save_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578969104,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void xen_save_time_memory_area()
```

```json
{
  "name": "xen_save_time_memory_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_save_time_memory_area",
      "external": true,
      "loc": "arch/x86/xen/time.c:382",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970167,
      "name": "xen_save_time_memory_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578969728,
      "name": "xen_save_time_memory_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void xen_save_time_memory_area()
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
void xen_save_time_memory_area()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_save_time_memory_area()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_save_time_memory_area()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_save_time_memory_area()
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
void xen_save_time_memory_area()
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
