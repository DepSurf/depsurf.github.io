# Function: <code>page_swap_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580758880,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:2738",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_set_page_dirty",
        "mm/swapfile.c:__page_file_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758880,
      "name": "page_swap_info.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071580774816,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580880293,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:2724",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898096,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580948245,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:2736",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966496,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580993221,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3216",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013456,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581098741,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3470",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581122336,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581239557,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3494",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581262832,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581322981,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3472",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345712,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581433973,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3476",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456032,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581498213,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3484",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581520192,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581703973,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3538",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581727712,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581751701,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3558",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:swap_page_sector"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775760,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581779525,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3529",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:swap_page_sector"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803312,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582062965,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3530",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:swap_page_sector"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582088160,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582501621,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3385",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_mapping",
        "mm/swapfile.c:swap_page_sector"
      ],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528112,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583015701,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3387",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_mapping",
        "mm/swapfile.c:swap_page_sector"
      ],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583042656,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583224389,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3375",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_mapping",
        "mm/swapfile.c:swap_page_sector"
      ],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583251264,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492919056,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3484",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492943512,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226709620,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3484",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226729792,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286326080,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3484",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286356928,
      "name": "page_swap_info",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272840422,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3484",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272860804,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581466949,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3484",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581488928,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581409205,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3484",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431184,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581458261,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3484",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480240,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct swap_info_struct * page_swap_info(struct page * page)
```

```json
{
  "name": "page_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581522693,
      "name": "page_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3484",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/page_io.c:swap_set_page_dirty",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544976,
      "name": "page_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct swap_info_struct * page_swap_info(struct page * page)
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
