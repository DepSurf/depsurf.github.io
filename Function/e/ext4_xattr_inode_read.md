# Function: <code>ext4_xattr_inode_read</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228832,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:318",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228832,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582377264,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:319",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582377264,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582568064,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:340",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582568064,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669456,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:340",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669456,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582844928,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:340",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582844928,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582949072,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:340",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949072,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583261232,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:342",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583261232,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583362160,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:342",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583362160,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583385104,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:342",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583385104,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:342",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583729424,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
    },
    {
      "addr": 18446744071592271869,
      "name": "ext4_xattr_inode_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:342",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584286352,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
    },
    {
      "addr": 18446744071594053684,
      "name": "ext4_xattr_inode_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:344",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584935040,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071596084987,
      "name": "ext4_xattr_inode_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:382",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585162592,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
    },
    {
      "addr": 18446744071596608481,
      "name": "ext4_xattr_inode_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:382",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585395360,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
    },
    {
      "addr": 18446744071597514136,
      "name": "ext4_xattr_inode_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494621240,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:340",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494621240,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228069724,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:340",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228069724,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288431232,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:340",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288431232,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273995018,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:340",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273995018,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582917808,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:340",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582917808,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582854960,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:340",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582854960,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906416,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:340",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906416,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582993488,
      "name": "ext4_xattr_inode_read",
      "external": false,
      "loc": "fs/ext4/xattr.c:340",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582993488,
      "name": "ext4_xattr_inode_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int ext4_xattr_inode_read(struct inode * ea_inode, void * buf, size_t size)
```
</details>
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
