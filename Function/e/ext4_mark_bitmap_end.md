# Function: <code>ext4_mark_bitmap_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581544416,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:52",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544416,
      "name": "ext4_mark_bitmap_end.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071581547440,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581732526,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:52",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730192,
      "name": "ext4_mark_bitmap_end.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071581733216,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581820126,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:52",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581817792,
      "name": "ext4_mark_bitmap_end.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071581820816,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581943712,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:54",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581941312,
      "name": "ext4_mark_bitmap_end.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071581944432,
      "name": "ext4_mark_bitmap_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582092818,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090624,
      "name": "ext4_mark_bitmap_end.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071582093824,
      "name": "ext4_mark_bitmap_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582280933,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280128,
      "name": "ext4_mark_bitmap_end.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071582281760,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582379669,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582377648,
      "name": "ext4_mark_bitmap_end.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071582380496,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582548195,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582546064,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582548928,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582649000,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582648192,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582649728,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582961025,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582958016,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582961648,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583035276,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583032192,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583035840,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583060632,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583058032,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071583061328,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583398575,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583395872,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071583399296,
      "name": "ext4_mark_bitmap_end",
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
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583913132,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583914128,
      "name": "ext4_mark_bitmap_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584539715,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584538544,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071584540240,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584768771,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584767648,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071584769280,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585001858,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585000720,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071585002368,
      "name": "ext4_mark_bitmap_end",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494301420,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494300200,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446603336494302544,
      "name": "ext4_mark_bitmap_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227735440,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227734616,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 3227736788,
      "name": "ext4_mark_bitmap_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288018100,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288017392,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 13835058055288019744,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273742670,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273742154,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446743936273743894,
      "name": "ext4_mark_bitmap_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582617736,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616928,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582618464,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582554904,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582554096,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582555632,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582607592,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606784,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582608320,
      "name": "ext4_mark_bitmap_end",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char * bitmap)
```

```json
{
  "name": "ext4_mark_bitmap_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582690170,
      "name": "ext4_mark_bitmap_end",
      "external": true,
      "loc": "fs/ext4/ialloc.c:55",
      "file": "fs/ext4/ialloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582689312,
      "name": "ext4_mark_bitmap_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582690992,
      "name": "ext4_mark_bitmap_end",
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
