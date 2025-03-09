# Function: <code>retpoline_module_ok</code>

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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579114592,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:101",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579114592,
      "name": "retpoline_module_ok",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121888,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:224",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121888,
      "name": "retpoline_module_ok",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579127904,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:221",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127904,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:375",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139813,
      "name": "retpoline_module_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579138704,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:497",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:check_modinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142005,
      "name": "retpoline_module_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579140816,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:600",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:check_modinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158555,
      "name": "retpoline_module_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579156080,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:598",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:check_modinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591252152,
      "name": "retpoline_module_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579153328,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:598",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:check_modinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591195758,
      "name": "retpoline_module_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579160864,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:636",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:check_modinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592061995,
      "name": "retpoline_module_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579191168,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:960",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:check_modinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593828557,
      "name": "retpoline_module_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579239488,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579298704,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:997",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:check_modinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298704,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305040,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1109",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:module_augment_kernel_taints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305040,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579335984,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1174",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:module_augment_kernel_taints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335984,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
  "name": "retpoline_module_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": false,
      "loc": "include/linux/module.h:878",
      "file": "kernel/module.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": false,
      "loc": "include/linux/module.h:878",
      "file": "kernel/module.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": false,
      "loc": "include/linux/module.h:878",
      "file": "kernel/module.c",
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
  "name": "retpoline_module_ok",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": false,
      "loc": "include/linux/module.h:878",
      "file": "kernel/module.c",
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:497",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:check_modinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142373,
      "name": "retpoline_module_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579141184,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:497",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:check_modinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073621,
      "name": "retpoline_module_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579072416,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:497",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:check_modinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141925,
      "name": "retpoline_module_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579140736,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool retpoline_module_ok(bool has_retpoline)
```

```json
{
  "name": "retpoline_module_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "retpoline_module_ok",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:497",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:check_modinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579147061,
      "name": "retpoline_module_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579145872,
      "name": "retpoline_module_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool retpoline_module_ok(bool has_retpoline)
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
bool retpoline_module_ok(bool has_retpoline)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool retpoline_module_ok(bool has_retpoline)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool retpoline_module_ok(bool has_retpoline)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool retpoline_module_ok(bool has_retpoline)
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
