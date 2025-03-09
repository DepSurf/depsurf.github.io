# Function: <code>_warn_unseeded_randomness</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584766992,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1478",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584766992,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585187088,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1477",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585187088,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1581",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585422848,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071585436016,
      "name": "_warn_unseeded_randomness.cold.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585559664,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1590",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585546496,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071585559664,
      "name": "_warn_unseeded_randomness.cold.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585779456,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1672",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585765888,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071585779456,
      "name": "_warn_unseeded_randomness.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585922160,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1672",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585908240,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071585922160,
      "name": "_warn_unseeded_randomness.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586657864,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1517",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:get_random_bytes"
      ],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586646416,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071586659152,
      "name": "_warn_unseeded_randomness.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586768392,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1516",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:get_random_bytes"
      ],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757120,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071591462117,
      "name": "_warn_unseeded_randomness.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586647656,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1492",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:get_random_bytes"
      ],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586638864,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071591403690,
      "name": "_warn_unseeded_randomness.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587195281,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1512",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:get_random_bytes"
      ],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587185792,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071592454532,
      "name": "_warn_unseeded_randomness.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498726224,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1672",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498726224,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231356648,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1672",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231356648,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291887248,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1672",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291887248,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276240136,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1672",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276240136,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585683136,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1672",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669232,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071585683136,
      "name": "_warn_unseeded_randomness.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585543008,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1672",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585529584,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071585543008,
      "name": "_warn_unseeded_randomness.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585872560,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1672",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585858640,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071585872560,
      "name": "_warn_unseeded_randomness.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```

```json
{
  "name": "_warn_unseeded_randomness",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585980432,
      "name": "_warn_unseeded_randomness",
      "external": false,
      "loc": "drivers/char/random.c:1672",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585967008,
      "name": "_warn_unseeded_randomness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071585980432,
      "name": "_warn_unseeded_randomness.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void _warn_unseeded_randomness(const char * func_name, void * caller, void * * previous)
```
</details>
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
