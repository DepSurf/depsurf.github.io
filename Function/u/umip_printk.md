# Function: <code>umip_printk</code>

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
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291296,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:116",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:force_sig_info_umip_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291296,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:116",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:force_sig_info_umip_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579303232,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071579304799,
      "name": "umip_printk.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:116",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327904,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071579329333,
      "name": "umip_printk.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:116",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343264,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071579344621,
      "name": "umip_printk.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:115",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347440,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071579348958,
      "name": "umip_printk.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:115",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377152,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071579378668,
      "name": "umip_printk.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:116",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579375824,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071591265013,
      "name": "umip_printk.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:116",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379440,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071591207218,
      "name": "umip_printk.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:116",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441072,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071592080537,
      "name": "umip_printk.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:116",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511104,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071593847876,
      "name": "umip_printk.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579610016,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:116",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579610016,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622640,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:116",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622640,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579651696,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:116",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579651696,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:115",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343344,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071579344862,
      "name": "umip_printk.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:115",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275616,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071579277075,
      "name": "umip_printk.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:115",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343264,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071579344782,
      "name": "umip_printk.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```

```json
{
  "name": "umip_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "umip_printk",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:115",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579351712,
      "name": "umip_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071579353230,
      "name": "umip_printk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
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
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void umip_printk(const struct pt_regs * regs, const char * log_level, const char * fmt, void (anon))
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
