# Function: <code>block_commit_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581217424,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2399",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581217424,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581395007,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2455",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/iomap.c:iomap_page_mkwrite_actor",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581381488,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581473375,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2496",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/iomap.c:iomap_page_mkwrite_actor",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459632,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581528594,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2490",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/iomap.c:iomap_page_mkwrite_actor",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581516160,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581670930,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2450",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/iomap.c:iomap_page_mkwrite_actor",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657872,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581834594,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2421",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/iomap.c:iomap_page_mkwrite_actor",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820512,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581921874,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2433",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907680,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582059177,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2430",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044656,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582136969,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2430",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582122432,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582376313,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2474",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582360496,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582432409,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2473",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582418128,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582459337,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2494",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445280,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582782985,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2473",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582766320,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583335574,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2472",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329872,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583920243,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2460",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583915040,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584130112,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2601",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584130112,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584346096,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2569",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584346096,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493682136,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2430",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493666568,
      "name": "block_commit_write",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227214568,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2430",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227197084,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287284816,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2430",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287262352,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273305596,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2430",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273291464,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582105705,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2430",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582091168,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582043145,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2430",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028688,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582096185,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2430",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081648,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int block_commit_write(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "block_commit_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582169076,
      "name": "block_commit_write",
      "external": true,
      "loc": "fs/buffer.c:2430",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154656,
      "name": "block_commit_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
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
