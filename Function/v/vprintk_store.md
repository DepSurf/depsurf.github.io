# Function: <code>vprintk_store</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579845264,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1828",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845264,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892288,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1840",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892288,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579926928,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1894",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926928,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579977072,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1904",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977072,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580024800,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1929",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580024800,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
int vprintk_store(int facility, int level, const struct dev_printk_info * dev_info, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580003568,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1959",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580003568,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1224
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
int vprintk_store(int facility, int level, const struct dev_printk_info * dev_info, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580005008,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:2035",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005008,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1222
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
int vprintk_store(int facility, int level, const struct dev_printk_info * dev_info, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:2098",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592133701,
      "name": "vprintk_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071580136832,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1442
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
int vprintk_store(int facility, int level, const struct dev_printk_info * dev_info, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:2117",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593904510,
      "name": "vprintk_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071580280512,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1414
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
int vprintk_store(int facility, int level, const struct dev_printk_info * dev_info, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:2205",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595985670,
      "name": "vprintk_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071580489216,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1429
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
int vprintk_store(int facility, int level, const struct dev_printk_info * dev_info, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:2153",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596503966,
      "name": "vprintk_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071580561072,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1422
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
int vprintk_store(int facility, int level, const struct dev_printk_info * dev_info, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:2149",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597401391,
      "name": "vprintk_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071580618096,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1422
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
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, va_list args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491160856,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1904",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491160856,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, va_list args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225188336,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1904",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225188336,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, va_list args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284059264,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1904",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284059264,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
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
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, va_list args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271715698,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1904",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271715698,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579945808,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1904",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945808,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579883808,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1904",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883808,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937344,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1904",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937344,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579983440,
      "name": "vprintk_store",
      "external": true,
      "loc": "kernel/printk/printk.c:1904",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983440,
      "name": "vprintk_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int vprintk_store(int facility, int level, const char * dict, size_t dictlen, const char * fmt, struct __va_list_tag * args)
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct dev_printk_info * dev_info</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * dict</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t dictlen</code>
</li>
<li>
<b>Param reordered. </b>
<code>facility, level, dict, dictlen, fmt, args</code> ➡️ <code>facility, level, dev_info, fmt, args</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
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
