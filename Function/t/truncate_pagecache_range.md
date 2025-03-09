# Function: <code>truncate_pagecache_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546576,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:778",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546576,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635968,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:799",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_write_begin",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635968,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703056,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:831",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_write_begin",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703056,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580736608,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:850",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736608,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823568,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:903",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823568,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580960384,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:894",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960384,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581036608,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:895",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_write_end",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036608,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581100448,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:898",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100448,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581157392,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:910",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157392,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343184,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:910",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343184,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581384912,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:938",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581384912,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581405120,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:829",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581405120,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581654928,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:828",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654928,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026640,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:846",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026640,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582460352,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:836",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460352,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582665504,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:836",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665504,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582836352,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:825",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836352,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492535376,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:910",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492535376,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226400476,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:910",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_failed",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226400476,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285831120,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:910",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285831120,
      "name": "truncate_pagecache_range",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272586024,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:910",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272586024,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581126240,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:910",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126240,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581073200,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:910",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581073200,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117440,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:910",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117440,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void truncate_pagecache_range(struct inode * inode, loff_t lstart, loff_t lend)
```

```json
{
  "name": "truncate_pagecache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581179904,
      "name": "truncate_pagecache_range",
      "external": true,
      "loc": "mm/truncate.c:910",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179904,
      "name": "truncate_pagecache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
