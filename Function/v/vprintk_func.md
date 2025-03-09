# Function: <code>vprintk_func</code>

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
  "name": "vprintk_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580543557,
      "name": "vprintk_func",
      "external": false,
      "loc": "kernel/printk/internal.h:34",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:printk"
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
  "name": "vprintk_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580607632,
      "name": "vprintk_func",
      "external": false,
      "loc": "kernel/printk/internal.h:34",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:printk"
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
int vprintk_func(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579783152,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:364",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783152,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int vprintk_func(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816528,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:361",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816528,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int vprintk_func(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850016,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:373",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850016,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int vprintk_func(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897024,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:373",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897024,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int vprintk_func(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931744,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:361",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931744,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int vprintk_func(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981872,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:361",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981872,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int vprintk_func(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029392,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:362",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029392,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int vprintk_func(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008016,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:370",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008016,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int vprintk_func(const char * fmt, va_list args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491167688,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:361",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491167688,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int vprintk_func(const char * fmt, va_list args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225193800,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:361",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225193800,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int vprintk_func(const char * fmt, va_list args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284066576,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:361",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284066576,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int vprintk_func(const char * fmt, va_list args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271720318,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:361",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271720318,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int vprintk_func(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579950608,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:361",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579950608,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int vprintk_func(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888496,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:361",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888496,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int vprintk_func(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942144,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:361",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942144,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int vprintk_func(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579988496,
      "name": "vprintk_func",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:361",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk",
        "kernel/printk/printk.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988496,
      "name": "vprintk_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int vprintk_func(const char * fmt, struct __va_list_tag * args)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int vprintk_func(const char * fmt, struct __va_list_tag * args)
```
</details>
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
