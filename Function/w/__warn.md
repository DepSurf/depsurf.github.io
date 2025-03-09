# Function: <code>__warn</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579381136,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:483",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:warn_slowpath_null",
        "kernel/panic.c:warn_slowpath_fmt_taint",
        "kernel/panic.c:warn_slowpath_fmt",
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381136,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579400224,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:513",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:warn_slowpath_null",
        "kernel/panic.c:warn_slowpath_fmt_taint",
        "kernel/panic.c:warn_slowpath_fmt",
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400224,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579387568,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:515",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387568,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414672,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:520",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414672,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:509",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579429932,
      "name": "__warn.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579428944,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:544",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579463628,
      "name": "__warn.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579462368,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:549",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481464,
      "name": "__warn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579480160,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:558",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507364,
      "name": "__warn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579506048,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:576",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535605,
      "name": "__warn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071579534384,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:576",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591277725,
      "name": "__warn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071579517248,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:576",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591220623,
      "name": "__warn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071579520400,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:574",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592099158,
      "name": "__warn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071579592144,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:601",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593866520,
      "name": "__warn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071579683664,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579806272,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:652",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806272,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854368,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:652",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854368,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892176,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:656",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892176,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490641184,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:558",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490641184,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224717432,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:558",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:warn_slowpath_fmt",
        "kernel/panic.c:warn_slowpath_fmt",
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224717432,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283459552,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:558",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283459552,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271393812,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:558",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271393812,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:558",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481028,
      "name": "__warn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579479712,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:558",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409912,
      "name": "__warn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579408608,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:558",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480948,
      "name": "__warn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579479632,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```

```json
{
  "name": "__warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__warn",
      "external": true,
      "loc": "kernel/panic.c:558",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bug.c:report_bug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512811,
      "name": "__warn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579511488,
      "name": "__warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void __warn(const char * file, int line, void * caller, unsigned int taint, struct pt_regs * regs, struct warn_args * args)
```
</details>
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
