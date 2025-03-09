# Function: <code>ext4_chunk_trans_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581569148,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5006",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:_ext4_get_block"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577216,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581755798,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5347",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765904,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581844771,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5491",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855056,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581994115,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5651",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002576,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582143993,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5704",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152576,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582332868,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5800",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340144,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582431477,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5852",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439264,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582600850,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5874",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582608736,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582701598,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5888",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582709648,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583013047,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5609",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_alloc",
        "fs/ext4/inode.c:ext4_writepages"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583021008,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583088295,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5700",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_alloc",
        "fs/ext4/inode.c:ext4_writepages"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583096624,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583113515,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5697",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121648,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583452825,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5636",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583462480,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583975251,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5714",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583985744,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584603315,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5853",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_do_writepages"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584614928,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584829346,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5665",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_do_writepages"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584841664,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585062210,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5685",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_do_writepages"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585074528,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494358724,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5888",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494367016,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227792388,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5888",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227801500,
      "name": "ext4_chunk_trans_blocks",
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288088956,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5888",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288099600,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273787746,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5888",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273794706,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582670334,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5888",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582678384,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582607502,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5888",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615552,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582660190,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5888",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582668240,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int ext4_chunk_trans_blocks(struct inode * inode, int nrblocks)
```

```json
{
  "name": "ext4_chunk_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582743886,
      "name": "ext4_chunk_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5888",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582752016,
      "name": "ext4_chunk_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
