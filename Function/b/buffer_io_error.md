# Function: <code>buffer_io_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581217040,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:135",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_write"
      ]
    },
    {
      "addr": 18446744071581595687,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:53",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581217040,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581381168,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:136",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071581786334,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581381168,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581459312,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:137",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071581875918,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459312,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581515552,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:137",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071582112446,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:54",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515552,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581657616,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:137",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071582261454,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657616,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:130",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071582449543,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820288,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071581838873,
      "name": "buffer_io_error.cold.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581926137,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:130",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071582549015,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907280,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071581926137,
      "name": "buffer_io_error.cold.61",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582063584,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:131",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071582721256,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044224,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071582063584,
      "name": "buffer_io_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582141421,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:131",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071582823820,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582121760,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071582141421,
      "name": "buffer_io_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582363648,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:126",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_write_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583135369,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:93",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582420928,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:126",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_write_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583216010,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:93",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582446848,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:126",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_write_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583243514,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:93",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582769408,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:126",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_write_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583585613,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:93",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583322500,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:126",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_write_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584123061,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:93",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583898944,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:126",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071584756661,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:93",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583898944,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584122432,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:126",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071584980137,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:93",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122432,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584339120,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:127",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071585211266,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:93",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584339120,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493660368,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:131",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446603336494494744,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493660368,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227195556,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:131",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 3227931768,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227195556,
      "name": "buffer_io_error",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287261840,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:131",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 13835058055288259344,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287261840,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273290312,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:131",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446743936273894146,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273290312,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582110157,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:131",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071582792556,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090496,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071582110157,
      "name": "buffer_io_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582047597,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:131",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071582729707,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028016,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071582047597,
      "name": "buffer_io_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582100637,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:131",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071582781436,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080976,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071582100637,
      "name": "buffer_io_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```

```json
{
  "name": "buffer_io_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582173507,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/buffer.c:131",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync"
      ]
    },
    {
      "addr": 18446744071582867776,
      "name": "buffer_io_error",
      "external": false,
      "loc": "fs/ext4/page-io.c:55",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582153952,
      "name": "buffer_io_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071582173507,
      "name": "buffer_io_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void buffer_io_error(struct buffer_head * bh, char * msg)
```
</details>
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
