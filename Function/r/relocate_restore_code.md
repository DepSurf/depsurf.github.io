# Function: <code>relocate_restore_code</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586580347,
      "name": "relocate_restore_code",
      "external": false,
      "loc": "arch/x86/power/hibernate_64.c:120",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
  "name": "relocate_restore_code",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586765019,
      "name": "relocate_restore_code",
      "external": false,
      "loc": "arch/x86/power/hibernate_64.c:124",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586888307,
      "name": "relocate_restore_code",
      "external": false,
      "loc": "arch/x86/power/hibernate_64.c:138",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587377151,
      "name": "relocate_restore_code",
      "external": false,
      "loc": "arch/x86/power/hibernate_64.c:138",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587681030,
      "name": "relocate_restore_code",
      "external": false,
      "loc": "arch/x86/power/hibernate_64.c:148",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587820240,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:211",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587820240,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588123344,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:211",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588123344,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588328144,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:211",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328144,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591150320,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:211",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591150320,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 637
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
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591236304,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:211",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591236304,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 637
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
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591179024,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:150",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591179024,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:150",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592759398,
      "name": "relocate_restore_code.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071592035088,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:150",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594647359,
      "name": "relocate_restore_code.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071593800512,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:150",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596373000,
      "name": "relocate_restore_code.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071595746304,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:150",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596902288,
      "name": "relocate_restore_code.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071596270592,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:150",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597827882,
      "name": "relocate_restore_code.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071597155328,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587934928,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:211",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587934928,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587648208,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:211",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587648208,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588266704,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:211",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588266704,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
int relocate_restore_code()
```

```json
{
  "name": "relocate_restore_code",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588401872,
      "name": "relocate_restore_code",
      "external": true,
      "loc": "arch/x86/power/hibernate.c:211",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588401872,
      "name": "relocate_restore_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int relocate_restore_code()
```
</details>
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
int relocate_restore_code()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int relocate_restore_code()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int relocate_restore_code()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int relocate_restore_code()
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
