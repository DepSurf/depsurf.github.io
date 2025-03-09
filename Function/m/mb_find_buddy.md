# Function: <code>mb_find_buddy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581782144,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:441",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782144,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581977008,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:441",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977008,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582067024,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:441",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582067024,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031920,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:439",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031920,
      "name": "mb_find_buddy",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582182080,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:439",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182080,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582372000,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:428",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582372000,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471632,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:428",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471632,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582641104,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:428",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641104,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582743024,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:428",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582743024,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583051680,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:451",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_regenerate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583051680,
      "name": "mb_find_buddy",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583127680,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:451",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583127680,
      "name": "mb_find_buddy",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583152976,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:508",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583152976,
      "name": "mb_find_buddy",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583503219,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:512",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_buddy_mark_free"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493760,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071592260041,
      "name": "mb_find_buddy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584033388,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:512",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021104,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071594041503,
      "name": "mb_find_buddy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584666476,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:515",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_buddy_mark_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584652160,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071596074302,
      "name": "mb_find_buddy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584890396,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:527",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_buddy_mark_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584875456,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071596597895,
      "name": "mb_find_buddy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585120588,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:527",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_buddy_mark_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585108320,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071597503457,
      "name": "mb_find_buddy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494407000,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:428",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494407000,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227839308,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:428",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227839308,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288145776,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:428",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288145776,
      "name": "mb_find_buddy",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273821968,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:428",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273821968,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582711760,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:428",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582711760,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582648928,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:428",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582648928,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582701616,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:428",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582701616,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void * mb_find_buddy(struct ext4_buddy * e4b, int order, int * max)
```

```json
{
  "name": "mb_find_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582786032,
      "name": "mb_find_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:428",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786032,
      "name": "mb_find_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
