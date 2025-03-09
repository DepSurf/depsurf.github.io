# Function: <code>insert_zspage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void insert_zspage(struct page * page, struct size_class * class, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580963616,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:650",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963616,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113968,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:754",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113968,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581189120,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:754",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189120,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237312,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:747",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237312,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581368832,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:751",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581368832,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518704,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:733",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518704,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581604592,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:733",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581604592,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715840,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:723",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715840,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789296,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:720",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789296,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582011296,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:720",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582011296,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582059776,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:716",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059776,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582084560,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:716",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582084560,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582396512,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:716",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582396512,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582907440,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:717",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907440,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583459936,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:765",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583459936,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583678657,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:691",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583872993,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:691",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493250608,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:720",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493250608,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226861252,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:720",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226861252,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286773200,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:720",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286773200,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273008104,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:720",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273008104,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758032,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:720",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758032,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581696656,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:720",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696656,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749344,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:720",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749344,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
```

```json
{
  "name": "insert_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581817664,
      "name": "insert_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:720",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:putback_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:fix_fullness_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581817664,
      "name": "insert_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct zspage * zspage</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, class, fullness</code> ➡️ <code>class, zspage, fullness</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void insert_zspage(struct size_class * class, struct zspage * zspage, enum fullness_group fullness)
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
