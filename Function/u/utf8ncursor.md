# Function: <code>utf8ncursor</code>

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
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583058837,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:583",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8cursor",
        "fs/unicode/utf8-norm.c:utf8cursor"
      ],
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
      "addr": 18446744071583058720,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583165253,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:583",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8cursor",
        "fs/unicode/utf8-norm.c:utf8cursor"
      ],
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
      "addr": 18446744071583165136,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583487829,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:583",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8cursor",
        "fs/unicode/utf8-norm.c:utf8cursor"
      ],
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
      "addr": 18446744071583487712,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583596117,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:583",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8cursor",
        "fs/unicode/utf8-norm.c:utf8cursor"
      ],
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
      "addr": 18446744071583596000,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583619125,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:583",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8cursor",
        "fs/unicode/utf8-norm.c:utf8cursor"
      ],
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
      "addr": 18446744071583619008,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583978149,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:583",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8cursor",
        "fs/unicode/utf8-norm.c:utf8cursor"
      ],
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
      "addr": 18446744071583978032,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int utf8ncursor(struct utf8cursor * u8c, const struct unicode_map * um, enum utf8_normalization n, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584558544,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:420",
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
      "addr": 18446744071584558544,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int utf8ncursor(struct utf8cursor * u8c, const struct unicode_map * um, enum utf8_normalization n, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585235808,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:420",
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
      "addr": 18446744071585235808,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int utf8ncursor(struct utf8cursor * u8c, const struct unicode_map * um, enum utf8_normalization n, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585465376,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:420",
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
      "addr": 18446744071585465376,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int utf8ncursor(struct utf8cursor * u8c, const struct unicode_map * um, enum utf8_normalization n, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585700352,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:420",
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
      "addr": 18446744071585700352,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494877996,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:583",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8cursor",
        "fs/unicode/utf8-norm.c:utf8cursor"
      ],
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
      "addr": 18446603336494877832,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228293564,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:583",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8cursor",
        "fs/unicode/utf8-norm.c:utf8cursor"
      ],
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
      "addr": 3228293428,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288737480,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:583",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8cursor",
        "fs/unicode/utf8-norm.c:utf8cursor"
      ],
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
      "addr": 13835058055288737344,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274195612,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:583",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8cursor",
        "fs/unicode/utf8-norm.c:utf8cursor"
      ],
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
      "addr": 18446743936274194976,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583133989,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:583",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8cursor",
        "fs/unicode/utf8-norm.c:utf8cursor"
      ],
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
      "addr": 18446744071583133872,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583071141,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:583",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8cursor",
        "fs/unicode/utf8-norm.c:utf8cursor"
      ],
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
      "addr": 18446744071583071024,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```

```json
{
  "name": "utf8ncursor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583211781,
      "name": "utf8ncursor",
      "external": true,
      "loc": "fs/unicode/utf8-norm.c:583",
      "file": "fs/unicode/utf8-norm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/unicode/utf8-norm.c:utf8cursor",
        "fs/unicode/utf8-norm.c:utf8cursor"
      ],
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
      "addr": 18446744071583211664,
      "name": "utf8ncursor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
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
<code>u8c, data, s, len</code> ➡️ <code>u8c, um, n, s, len</code>
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
int utf8ncursor(struct utf8cursor * u8c, const struct utf8data * data, const char * s, size_t len)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
