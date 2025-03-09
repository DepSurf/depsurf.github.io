# Function: <code>putback_zspage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum fullness_group putback_zspage(struct zs_pool * pool, struct size_class * class, struct page * first_page)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580964368,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1686",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580964368,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581114288,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1856",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581114288,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581189376,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1816",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189376,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237584,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1795",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237584,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369104,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1799",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369104,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581519008,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1802",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519008,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581604896,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1789",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581604896,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716144,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1779",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716144,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789600,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1776",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789600,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582016993,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1778",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__zs_compact"
      ],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582013952,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582065481,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1727",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__zs_compact"
      ],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062432,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582089578,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1726",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact"
      ],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086640,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582402160,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1725",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact"
      ],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582399568,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582918179,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1702",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__zs_compact"
      ],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582910912,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583472464,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1910",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__zs_compact"
      ],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583462976,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
int putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583678560,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1676",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583678560,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
int putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872896,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1658",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872896,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493251040,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1776",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493251040,
      "name": "putback_zspage",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226861620,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1776",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226861620,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286773568,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1776",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286773568,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273008450,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1776",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273008450,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758336,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1776",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758336,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581696960,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1776",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696960,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749648,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1776",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749648,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
enum fullness_group putback_zspage(struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "putback_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581817968,
      "name": "putback_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1776",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581817968,
      "name": "putback_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
<code>struct zs_pool * pool</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * first_page</code>
</li>
<li>
<b>Param reordered. </b>
<code>pool, class, first_page</code> ➡️ <code>class, zspage</code>
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
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>enum fullness_group</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
