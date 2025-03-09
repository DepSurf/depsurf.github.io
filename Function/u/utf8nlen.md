# Function: <code>utf8nlen</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583058448,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:548",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583058448,
      "name": "utf8nlen",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583164864,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:548",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164864,
      "name": "utf8nlen",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583487424,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:548",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583487424,
      "name": "utf8nlen.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071583487680,
      "name": "utf8nlen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583595696,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:548",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583595696,
      "name": "utf8nlen.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071583595968,
      "name": "utf8nlen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583618736,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:548",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583618736,
      "name": "utf8nlen",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583977728,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:548",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583977728,
      "name": "utf8nlen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t utf8nlen(const struct unicode_map * um, enum utf8_normalization n, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584558080,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:386",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584558080,
      "name": "utf8nlen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
ssize_t utf8nlen(const struct unicode_map * um, enum utf8_normalization n, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585235328,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:386",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585235328,
      "name": "utf8nlen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
ssize_t utf8nlen(const struct unicode_map * um, enum utf8_normalization n, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585464896,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:386",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585464896,
      "name": "utf8nlen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
ssize_t utf8nlen(const struct unicode_map * um, enum utf8_normalization n, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585699872,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:386",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585699872,
      "name": "utf8nlen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494877456,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:548",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494877456,
      "name": "utf8nlen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228293128,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:548",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228293128,
      "name": "utf8nlen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288736864,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:548",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288736864,
      "name": "utf8nlen",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274195338,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:548",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274195338,
      "name": "utf8nlen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583133600,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:548",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583133600,
      "name": "utf8nlen",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583070752,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:548",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583070752,
      "name": "utf8nlen",
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8nlen",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583211392,
      "name": "utf8nlen",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:548",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211392,
      "name": "utf8nlen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct unicode_map * um</code>
</li>
<li>
<b>Param added. </b>
<code>enum utf8_normalization n</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct utf8data * data</code>
</li>
<li>
<b>Param reordered. </b>
<code>data, s, len</code> ➡️ <code>um, n, s, len</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
ssize_t utf8nlen(const struct utf8data * data, const char * s, size_t len)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
