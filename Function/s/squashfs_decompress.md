# Function: <code>squashfs_decompress</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582144352,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_multi_percpu.c:77",
      "file": "fs/squashfs/decompressor_multi_percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582144352,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582233824,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:64",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582233824,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318576,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:64",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318576,
      "name": "squashfs_decompress",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582467952,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:64",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582467952,
      "name": "squashfs_decompress",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:64",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659104,
      "name": "squashfs_decompress.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582658944,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:64",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760992,
      "name": "squashfs_decompress.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582760832,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582935248,
      "name": "squashfs_decompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582935072,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583041872,
      "name": "squashfs_decompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583041696,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583359824,
      "name": "squashfs_decompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583359664,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591351817,
      "name": "squashfs_decompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583475792,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591294731,
      "name": "squashfs_decompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583498000,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592276538,
      "name": "squashfs_decompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583852928,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_multi_percpu.c:78",
      "file": "fs/squashfs/decompressor_multi_percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594058461,
      "name": "squashfs_decompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584423024,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585081536,
      "name": "squashfs_decompress",
      "external": false,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585082016,
      "name": "squashfs_decompress",
      "external": false,
      "loc": "fs/squashfs/decompressor_multi.c:182",
      "file": "fs/squashfs/decompressor_multi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585082976,
      "name": "squashfs_decompress",
      "external": false,
      "loc": "fs/squashfs/decompressor_multi_percpu.c:78",
      "file": "fs/squashfs/decompressor_multi_percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585081536,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071585082016,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071585082976,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int squashfs_decompress(struct squashfs_sb_info * msblk, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585311152,
      "name": "squashfs_decompress",
      "external": false,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585311632,
      "name": "squashfs_decompress",
      "external": false,
      "loc": "fs/squashfs/decompressor_multi.c:182",
      "file": "fs/squashfs/decompressor_multi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585312592,
      "name": "squashfs_decompress",
      "external": false,
      "loc": "fs/squashfs/decompressor_multi_percpu.c:77",
      "file": "fs/squashfs/decompressor_multi_percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311152,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071585311632,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071585312592,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int squashfs_decompress(struct squashfs_sb_info * msblk, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585545472,
      "name": "squashfs_decompress",
      "external": false,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585545952,
      "name": "squashfs_decompress",
      "external": false,
      "loc": "fs/squashfs/decompressor_multi.c:182",
      "file": "fs/squashfs/decompressor_multi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585547040,
      "name": "squashfs_decompress",
      "external": false,
      "loc": "fs/squashfs/decompressor_multi_percpu.c:77",
      "file": "fs/squashfs/decompressor_multi_percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585545472,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071585545952,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
    },
    {
      "addr": 18446744071585547040,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494737832,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494737832,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228173376,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228173376,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288563984,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288563984,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274084298,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274084298,
      "name": "squashfs_decompress",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010608,
      "name": "squashfs_decompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583010432,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582947760,
      "name": "squashfs_decompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582947584,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582999216,
      "name": "squashfs_decompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582999040,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "squashfs_decompress",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_decompress",
      "external": true,
      "loc": "fs/squashfs/decompressor_single.c:62",
      "file": "fs/squashfs/decompressor_single.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583088448,
      "name": "squashfs_decompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583088272,
      "name": "squashfs_decompress",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int squashfs_decompress(struct squashfs_sb_info * msblk, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bio * bio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct buffer_head * * bh</code>
</li>
<li>
<b>Param removed. </b>
<code>int b</code>
</li>
<li>
<b>Param reordered. </b>
<code>msblk, bh, b, offset, length, output</code> ➡️ <code>msblk, bio, offset, length, output</code>
</li>
</ul>
</details>
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
