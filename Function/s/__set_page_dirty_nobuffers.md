# Function: <code>__set_page_dirty_nobuffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580526992,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2459",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526992,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580611232,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2505",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580611232,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580678464,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2472",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580678464,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580711696,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2475",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580711696,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580797264,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2458",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797264,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580928496,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2459",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928496,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581005120,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2453",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581005120,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581078848,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2461",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078848,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581134832,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2465",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134832,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581319344,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2475",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319344,
      "name": "__set_page_dirty_nobuffers.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071581319632,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581361280,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2473",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361280,
      "name": "__set_page_dirty_nobuffers.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071581361568,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581380496,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2473",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581380496,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581630208,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2519",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581630208,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995072,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/folio-compat.c:88",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995072,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582431376,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/folio-compat.c:60",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431376,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582636736,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/folio-compat.c:61",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582636736,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582808112,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/folio-compat.c:61",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808112,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492507792,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2465",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492507792,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226379640,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2465",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226379640,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285797280,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2465",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285797280,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272567646,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2465",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272567646,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581103680,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2465",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103680,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581050800,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2465",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050800,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581094880,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2465",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094880,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int __set_page_dirty_nobuffers(struct page * page)
```

```json
{
  "name": "__set_page_dirty_nobuffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581157088,
      "name": "__set_page_dirty_nobuffers",
      "external": true,
      "loc": "mm/page-writeback.c:2465",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:redirty_page_for_writepage",
        "fs/ext4/inode.c:ext4_journalled_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157088,
      "name": "__set_page_dirty_nobuffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
