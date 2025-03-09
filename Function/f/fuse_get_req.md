# Function: <code>fuse_get_req</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_req * fuse_get_req(struct fuse_conn * fc, unsigned int npages)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582052912,
      "name": "fuse_get_req",
      "external": true,
      "loc": "fs/fuse/dev.c:202",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052912,
      "name": "fuse_get_req",
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, unsigned int npages)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582268327,
      "name": "fuse_get_req",
      "external": true,
      "loc": "fs/fuse/dev.c:182",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266784,
      "name": "fuse_get_req",
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, unsigned int npages)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582357616,
      "name": "fuse_get_req",
      "external": true,
      "loc": "fs/fuse/dev.c:182",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582356368,
      "name": "fuse_get_req",
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, unsigned int npages)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582441572,
      "name": "fuse_get_req",
      "external": true,
      "loc": "fs/fuse/dev.c:182",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440352,
      "name": "fuse_get_req",
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, unsigned int npages)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582592065,
      "name": "fuse_get_req",
      "external": true,
      "loc": "fs/fuse/dev.c:182",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582590832,
      "name": "fuse_get_req",
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, unsigned int npages)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582787766,
      "name": "fuse_get_req",
      "external": true,
      "loc": "fs/fuse/dev.c:192",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582783360,
      "name": "fuse_get_req",
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, unsigned int npages)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582892950,
      "name": "fuse_get_req",
      "external": true,
      "loc": "fs/fuse/dev.c:232",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582887504,
      "name": "fuse_get_req",
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, unsigned int npages)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583068746,
      "name": "fuse_get_req",
      "external": true,
      "loc": "fs/fuse/dev.c:232",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_request"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583066672,
      "name": "fuse_get_req",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fuse_req * fuse_get_req(struct fuse_conn * fc, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583169280,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:105",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169280,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583491392,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:105",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491392,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
struct fuse_req * fuse_get_req(struct fuse_mount * fm, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583599792,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:106",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583599792,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
struct fuse_req * fuse_get_req(struct fuse_mount * fm, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583622576,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:106",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583622576,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 670
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
struct fuse_req * fuse_get_req(struct fuse_mount * fm, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583981600,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:106",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583981600,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 670
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
struct fuse_req * fuse_get_req(struct fuse_mount * fm, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584566144,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:106",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584566144,
      "name": "fuse_get_req",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fuse_req * fuse_get_req(struct fuse_mount * fm, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585242976,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:106",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242976,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
struct fuse_req * fuse_get_req(struct fuse_mount * fm, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585472768,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:106",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585472768,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
struct fuse_req * fuse_get_req(struct fuse_mount * fm, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585707792,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:106",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585707792,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494883856,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:105",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494883856,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228297864,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:105",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_retrieve",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228297864,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288744640,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:105",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288744640,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274199710,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:105",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274199710,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583138016,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:105",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138016,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583075168,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:105",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583075168,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583122048,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:105",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122048,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
struct fuse_req * fuse_get_req(struct fuse_conn * fc, bool for_background)
```

```json
{
  "name": "fuse_get_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583217136,
      "name": "fuse_get_req",
      "external": false,
      "loc": "fs/fuse/dev.c:105",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583217136,
      "name": "fuse_get_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool for_background</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int npages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_mount * fm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_conn * fc</code>
</li>
</ul>
</details>
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
