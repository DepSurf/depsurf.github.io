# Function: <code>ext4_walk_page_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571152,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:830",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571152,
      "name": "ext4_walk_page_buffers",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581784688,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:998",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581757120,
      "name": "ext4_walk_page_buffers",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581874240,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1012",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845936,
      "name": "ext4_walk_page_buffers",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582022080,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1062",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995584,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582172688,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1072",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145520,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582362595,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1073",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582334592,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582461603,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1073",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433216,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582630643,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1081",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602624,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582731779,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1090",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582703440,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583040160,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:939",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014688,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583115930,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:956",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583089952,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583141626,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:957",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583114912,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int ext4_walk_page_buffers(handle_t * handle, struct inode * inode, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct inode *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583482158,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:958",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583454336,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int ext4_walk_page_buffers(handle_t * handle, struct inode * inode, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct inode *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584006452,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:971",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583976928,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int ext4_walk_page_buffers(handle_t * handle, struct inode * inode, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct inode *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584636574,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:977",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584605232,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int ext4_walk_page_buffers(handle_t * handle, struct inode * inode, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct inode *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584860032,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:932",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_journal_folio_buffers",
        "fs/ext4/inode.c:ext4_journal_folio_buffers",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584831280,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int ext4_walk_page_buffers(handle_t * handle, struct inode * inode, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct inode *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585092959,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:946",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_journal_folio_buffers",
        "fs/ext4/inode.c:ext4_journal_folio_buffers",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585064160,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494388628,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1090",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494360800,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227826880,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1090",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227794816,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288129004,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1090",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288091792,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273812816,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1090",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273789348,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582700515,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1090",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582672176,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582637683,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1090",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609344,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582690371,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1090",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582662032,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int ext4_walk_page_buffers(handle_t * handle, struct buffer_head * head, unsigned int from, unsigned int to, int * partial, int (*)(handle_t *, struct buffer_head *) fn)
```

```json
{
  "name": "ext4_walk_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582774670,
      "name": "ext4_walk_page_buffers",
      "external": true,
      "loc": "fs/ext4/inode.c:1090",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745696,
      "name": "ext4_walk_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>handle, head, from, to, partial, fn</code> ➡️ <code>handle, inode, head, from, to, partial, fn</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*)(handle_t *, struct buffer_head *) fn</code> ➡️ <code>int (*)(handle_t *, struct inode *, struct buffer_head *) fn</code>
</li>
</ul>
</details>
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
