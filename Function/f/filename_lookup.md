# Function: <code>filename_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581057504,
      "name": "filename_lookup",
      "external": false,
      "loc": "fs/namei.c:2153",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:user_path_at_empty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057504,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218400,
      "name": "filename_lookup",
      "external": false,
      "loc": "fs/namei.c:2290",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218400,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296096,
      "name": "filename_lookup",
      "external": false,
      "loc": "fs/namei.c:2279",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296096,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345648,
      "name": "filename_lookup",
      "external": false,
      "loc": "fs/namei.c:2324",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345648,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487040,
      "name": "filename_lookup",
      "external": false,
      "loc": "fs/namei.c:2322",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487040,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581647683,
      "name": "filename_lookup",
      "external": false,
      "loc": "fs/namei.c:2309",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path"
      ],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647104,
      "name": "filename_lookup.part.59",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581733955,
      "name": "filename_lookup",
      "external": false,
      "loc": "fs/namei.c:2336",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path"
      ],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581733376,
      "name": "filename_lookup.part.60",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852752,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2334",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852752,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581925232,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2327",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925232,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582155408,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2354",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582155408,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582200912,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2352",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200912,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582225664,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2442",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582225664,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582542688,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2470",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542688,
      "name": "filename_lookup",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583070336,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2516",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param",
        "io_uring/io_uring.c:io_setxattr",
        "io_uring/io_uring.c:io_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583070336,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583636720,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2495",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param",
        "io_uring/xattr.c:io_setxattr",
        "io_uring/xattr.c:io_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583636720,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583853872,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2500",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param",
        "io_uring/xattr.c:io_setxattr",
        "io_uring/xattr.c:io_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583853872,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584061056,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2507",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/namei.c:do_linkat",
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param",
        "io_uring/xattr.c:io_setxattr",
        "io_uring/xattr.c:io_getxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061056,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493405776,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2327",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493405776,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226991616,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2327",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226991616,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286964096,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2327",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286964096,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273117186,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2327",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273117186,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581893968,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2327",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581893968,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831568,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2327",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831568,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885280,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2327",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885280,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```

```json
{
  "name": "filename_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954784,
      "name": "filename_lookup",
      "external": true,
      "loc": "fs/namei.c:2327",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/fs_parser.c:fs_lookup_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954784,
      "name": "filename_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int filename_lookup(int dfd, struct filename * name, unsigned int flags, struct path * path, struct path * root)
```
</details>
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
