# Function: <code>utf8byte</code>

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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583056672,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:652",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583056672,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 935
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583163088,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:652",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583163088,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 935
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583485600,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:652",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583485600,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 967
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583593856,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:652",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold_hash",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583593856,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 967
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583616944,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:652",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold_hash",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616944,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583975552,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:652",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold_hash",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583975552,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1019
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584558688,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:471",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold_hash",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584558688,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1154
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585235968,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:471",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold_hash",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585235968,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585465536,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:471",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold_hash",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585465536,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585700512,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:471",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold_hash",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585700512,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494875432,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:652",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494875432,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228291252,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:652",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228291252,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288734048,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:652",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288734048,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1276
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274193738,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:652",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274193738,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 670
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583131824,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:652",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583131824,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 935
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583068976,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:652",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068976,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 935
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
int utf8byte(struct utf8cursor * u8c)
```

```json
{
  "name": "utf8byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583209616,
      "name": "utf8byte",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:652",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/unicode/utf8-core.c:utf8_normalize",
        "fs/unicode/utf8-core.c:utf8_casefold",
        "fs/unicode/utf8-core.c:utf8_strncasecmp_folded",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncasecmp",
        "fs/unicode/utf8-core.c:utf8_strncmp",
        "fs/unicode/utf8-core.c:utf8_strncmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583209616,
      "name": "utf8byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 935
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
int utf8byte(struct utf8cursor * u8c)
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
int utf8byte(struct utf8cursor * u8c)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
