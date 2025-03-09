# Function: <code>ext4_init_io_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581596352,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:265",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581596352,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581787008,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:251",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787008,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581876592,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:251",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581876592,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582113200,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:250",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582113200,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262208,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:251",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262208,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582450256,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:251",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450256,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582549728,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:251",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549728,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582721984,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:243",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582721984,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582824464,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:243",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582824464,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583136288,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:277",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583136288,
      "name": "ext4_init_io_end",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583216928,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:274",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583216928,
      "name": "ext4_init_io_end",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583244400,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:274",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244400,
      "name": "ext4_init_io_end",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583586528,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:274",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583586528,
      "name": "ext4_init_io_end",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584124288,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:276",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124288,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584758000,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:276",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758000,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584981888,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:276",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584981888,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585213248,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:276",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585213248,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494496016,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:243",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494496016,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227932488,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:243",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227932488,
      "name": "ext4_init_io_end",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288260656,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:243",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288260656,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273895716,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:243",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273895716,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582793200,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:243",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582793200,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582730352,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:243",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582730352,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582782080,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:243",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582782080,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
ext4_io_end_t * ext4_init_io_end(struct inode * inode, gfp_t flags)
```

```json
{
  "name": "ext4_init_io_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582868448,
      "name": "ext4_init_io_end",
      "external": true,
      "loc": "fs/ext4/page-io.c:243",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582868448,
      "name": "ext4_init_io_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
