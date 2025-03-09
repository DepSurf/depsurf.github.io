# Function: <code>ext4_convert_unwritten_extents</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767472,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:5026",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_end_io_unwritten",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work",
        "fs/ext4/page-io.c:ext4_put_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767472,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581962256,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:5028",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962256,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052368,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:5008",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052368,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581914448,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:5004",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581914448,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064656,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:5007",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064656,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582252736,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:5003",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582252736,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582348336,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4902",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348336,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582518688,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4912",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582518688,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582618768,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4958",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582618768,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582929728,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4722",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec",
        "fs/ext4/file.c:ext4_dio_write_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582929728,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583001440,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4731",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec",
        "fs/ext4/file.c:ext4_dio_write_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583001440,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583026944,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4737",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec",
        "fs/ext4/file.c:ext4_dio_write_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583026944,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4775",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec",
        "fs/ext4/file.c:ext4_dio_write_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592253428,
      "name": "ext4_convert_unwritten_extents.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071583363808,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4778",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec",
        "fs/ext4/file.c:ext4_dio_write_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594034436,
      "name": "ext4_convert_unwritten_extents.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071583875216,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 643
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4782",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec",
        "fs/ext4/file.c:ext4_dio_write_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596067662,
      "name": "ext4_convert_unwritten_extents.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071584499568,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4781",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec",
        "fs/ext4/file.c:ext4_dio_write_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596591304,
      "name": "ext4_convert_unwritten_extents.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071584728096,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4816",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec",
        "fs/ext4/file.c:ext4_dio_write_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597497092,
      "name": "ext4_convert_unwritten_extents.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071584960720,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494267984,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4958",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494267984,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227701240,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4958",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227701240,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287977376,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4958",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287977376,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273716310,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4958",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273716310,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582587504,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4958",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582587504,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582524672,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4958",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582524672,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582577616,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4958",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582577616,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
int ext4_convert_unwritten_extents(handle_t * handle, struct inode * inode, loff_t offset, ssize_t len)
```

```json
{
  "name": "ext4_convert_unwritten_extents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582659056,
      "name": "ext4_convert_unwritten_extents",
      "external": true,
      "loc": "fs/ext4/extents.c:4958",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659056,
      "name": "ext4_convert_unwritten_extents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
