# Function: <code>__zswap_pool_current</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580778998,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:496",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580904246,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:498",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store"
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
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580972266,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:422",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581016400,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:426",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_pool_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581016400,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581125408,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:426",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125408,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581267872,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:441",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267872,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581351568,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:441",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351568,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581462016,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:432",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462016,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581526096,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:432",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581526096,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581733200,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:449",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581733200,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581781104,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:503",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781104,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581808704,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:503",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808704,
      "name": "__zswap_pool_current",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582094533,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:503",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094480,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071592210161,
      "name": "__zswap_pool_current.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:518",
      "file": "mm/zswap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582533344,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071593988302,
      "name": "__zswap_pool_current.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:518",
      "file": "mm/zswap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048416,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071596039793,
      "name": "__zswap_pool_current.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583263920,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:532",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583257024,
      "name": "__zswap_pool_current.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071596561941,
      "name": "__zswap_pool_current.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583497249,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:766",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty",
        "mm/zswap.c:zswap_pool_current_get"
      ],
      "caller_func": [
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty",
        "mm/zswap.c:zswap_pool_current_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583490656,
      "name": "__zswap_pool_current.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071597467555,
      "name": "__zswap_pool_current.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492953816,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:432",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_pool_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492953816,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226736660,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:432",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_pool_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226736660,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286366528,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:432",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_pool_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286366528,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272867628,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:432",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272867628,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581494832,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:432",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581494832,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581437072,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:432",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437072,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581486144,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:432",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486144,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct zswap_pool * __zswap_pool_current()
```

```json
{
  "name": "__zswap_pool_current",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581550816,
      "name": "__zswap_pool_current",
      "external": false,
      "loc": "mm/zswap.c:432",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_pool_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581550816,
      "name": "__zswap_pool_current",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
struct zswap_pool * __zswap_pool_current()
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct zswap_pool * __zswap_pool_current()
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
