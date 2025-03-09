# Function: <code>truncate_pagecache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546400,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:670",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546400,
      "name": "truncate_pagecache",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635792,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:691",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635792,
      "name": "truncate_pagecache",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580702880,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:723",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702880,
      "name": "truncate_pagecache",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580736432,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:742",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736432,
      "name": "truncate_pagecache",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823392,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:795",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823392,
      "name": "truncate_pagecache",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580960192,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:786",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960192,
      "name": "truncate_pagecache",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581036416,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:787",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036416,
      "name": "truncate_pagecache",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581100256,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:790",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100256,
      "name": "truncate_pagecache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581157200,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:802",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157200,
      "name": "truncate_pagecache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581342992,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:802",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/inode.c:fat_direct_IO",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/inode.c:fat_write_begin",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342992,
      "name": "truncate_pagecache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581384720,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:830",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/inode.c:fat_direct_IO",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/inode.c:fat_write_begin",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581384720,
      "name": "truncate_pagecache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581404928,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:721",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/inode.c:fat_direct_IO",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/inode.c:fat_write_begin",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404928,
      "name": "truncate_pagecache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581654736,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:720",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/inode.c:fat_direct_IO",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/inode.c:fat_write_begin",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654736,
      "name": "truncate_pagecache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026432,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:738",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/inode.c:fat_direct_IO",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/inode.c:fat_write_begin",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/file.c:fuse_open_common",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026432,
      "name": "truncate_pagecache",
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582460112,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:728",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/inode.c:fat_direct_IO",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/inode.c:fat_write_begin",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/file.c:fuse_open_common",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460112,
      "name": "truncate_pagecache",
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582665264,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:728",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/inode.c:fat_direct_IO",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/inode.c:fat_write_begin",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/file.c:fuse_open_common",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665264,
      "name": "truncate_pagecache",
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582836112,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:717",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/inode.c:fat_direct_IO",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/inode.c:fat_write_begin",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/file.c:fuse_open_common",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836112,
      "name": "truncate_pagecache",
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492535152,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:802",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492535152,
      "name": "truncate_pagecache",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226400188,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:802",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/inode.c:fat_write_failed",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226400188,
      "name": "truncate_pagecache",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285830848,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:802",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/inode.c:fat_write_failed",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285830848,
      "name": "truncate_pagecache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272585846,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:802",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/inode.c:fat_write_failed",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272585846,
      "name": "truncate_pagecache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581126048,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:802",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126048,
      "name": "truncate_pagecache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581073008,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:802",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581073008,
      "name": "truncate_pagecache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117248,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:802",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117248,
      "name": "truncate_pagecache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void truncate_pagecache(struct inode * inode, loff_t newsize)
```

```json
{
  "name": "truncate_pagecache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581179712,
      "name": "truncate_pagecache",
      "external": true,
      "loc": "mm/truncate.c:802",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_setsize",
        "mm/truncate.c:truncate_setsize",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/inode.c:fuse_change_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179712,
      "name": "truncate_pagecache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
