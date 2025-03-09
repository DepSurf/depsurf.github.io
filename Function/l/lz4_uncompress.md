# Function: <code>lz4_uncompress</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583098577,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "lib/lz4/lz4_decompress.c:55",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/lz4/lz4_decompress.c:lz4_decompress"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582146128,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:93",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583392768,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "lib/lz4/lz4_decompress.c:55",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/lz4/lz4_decompress.c:lz4_decompress"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146128,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582235648,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:93",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583518144,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "lib/lz4/lz4_decompress.c:55",
      "file": "lib/lz4/lz4_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/lz4/lz4_decompress.c:lz4_decompress"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235648,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582320416,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:93",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320416,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582469808,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:93",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582469808,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660768,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:93",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660768,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582762656,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:93",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582762656,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582936912,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582936912,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583043536,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583043536,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583361568,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361568,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583477776,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583477776,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583499984,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583499984,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583854912,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583854912,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584425184,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584425184,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585086016,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585086016,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585315632,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585315632,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585550080,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585550080,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494740096,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494740096,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228175384,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228175384,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288566640,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288566640,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274085988,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274085988,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583012272,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583012272,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582949424,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949424,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583000880,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583000880,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "lz4_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583090112,
      "name": "lz4_uncompress",
      "external": false,
      "loc": "fs/squashfs/lz4_wrapper.c:91",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583090112,
      "name": "lz4_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int lz4_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
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
<code>msblk, strm, bh, b, offset, length, output</code> ➡️ <code>msblk, strm, bio, offset, length, output</code>
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
