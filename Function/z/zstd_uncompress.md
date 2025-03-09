# Function: <code>zstd_uncompress</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582472672,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:70",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582472672,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:70",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582663664,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071582664402,
      "name": "zstd_uncompress.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:70",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582765552,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071582766290,
      "name": "zstd_uncompress.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582939824,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    },
    {
      "addr": 18446744071582940563,
      "name": "zstd_uncompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583046448,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    },
    {
      "addr": 18446744071583047187,
      "name": "zstd_uncompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583364896,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
    },
    {
      "addr": 18446744071583365635,
      "name": "zstd_uncompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583480960,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
    },
    {
      "addr": 18446744071591351977,
      "name": "zstd_uncompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583503120,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
    },
    {
      "addr": 18446744071591294892,
      "name": "zstd_uncompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858080,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
    },
    {
      "addr": 18446744071592276829,
      "name": "zstd_uncompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584428576,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 629
    },
    {
      "addr": 18446744071594058762,
      "name": "zstd_uncompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585089824,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585089824,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585319360,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319360,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 679
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct bio * bio, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585554048,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585554048,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 679
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494743152,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494743152,
      "name": "zstd_uncompress",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228178132,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228178132,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288570736,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288570736,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274088346,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274088346,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015184,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    },
    {
      "addr": 18446744071583015923,
      "name": "zstd_uncompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952336,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    },
    {
      "addr": 18446744071582953075,
      "name": "zstd_uncompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583003792,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    },
    {
      "addr": 18446744071583004531,
      "name": "zstd_uncompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```

```json
{
  "name": "zstd_uncompress",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zstd_uncompress",
      "external": false,
      "loc": "fs/squashfs/zstd_wrapper.c:61",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583093024,
      "name": "zstd_uncompress",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    },
    {
      "addr": 18446744071583093763,
      "name": "zstd_uncompress.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int zstd_uncompress(struct squashfs_sb_info * msblk, void * strm, struct buffer_head * * bh, int b, int offset, int length, struct squashfs_page_actor * output)
```
</details>
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
