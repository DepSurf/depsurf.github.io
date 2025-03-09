# Function: <code>utf8_strncasecmp</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583059344,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:49",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583059344,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583165760,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:49",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583165760,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583488336,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:49",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_ci_compare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583488336,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583596624,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:50",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_ci_d_compare",
        "fs/ext4/namei.c:ext4_ci_compare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583596624,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583619632,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:50",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_ci_d_compare",
        "fs/ext4/namei.c:ext4_ci_compare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619632,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583978656,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:50",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_ci_d_compare",
        "fs/ext4/namei.c:ext4_ci_compare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583978656,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584560144,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:46",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_ci_d_compare",
        "fs/ext4/namei.c:ext4_ci_compare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584560144,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585237456,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:46",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_ci_d_compare",
        "fs/ext4/namei.c:ext4_ci_compare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585237456,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585467024,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:46",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_ci_d_compare",
        "fs/ext4/namei.c:ext4_ci_compare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585467024,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585702000,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:46",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_ci_d_compare",
        "fs/ext4/namei.c:ext4_ci_compare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585702000,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494878552,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:49",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494878552,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228294132,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:49",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228294132,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288738208,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:49",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288738208,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274196078,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:49",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274196078,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583134496,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:49",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583134496,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583071648,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:49",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583071648,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```

```json
{
  "name": "utf8_strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583212288,
      "name": "utf8_strncasecmp",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:49",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583212288,
      "name": "utf8_strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
int utf8_strncasecmp(const struct unicode_map * um, const struct qstr * s1, const struct qstr * s2)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
