# Function: <code>vfs_getattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vfs_getattr(struct path * path, struct kstat * stat)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581013232,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:65",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:copy_file_from_fd",
        "fs/stat.c:vfs_fstat",
        "fs/stat.c:vfs_fstatat",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/loop.c:loop_get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013232,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int vfs_getattr(struct path * path, struct kstat * stat)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581171616,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:65",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_fstatat",
        "fs/stat.c:vfs_fstat",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/loop.c:loop_get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171616,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int vfs_getattr(struct path * path, struct kstat * stat)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248608,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:65",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_fstatat",
        "fs/stat.c:vfs_fstat",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/loop.c:loop_get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248608,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296416,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:107",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/loop.c:loop_get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296416,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581436272,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:108",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/loop.c:loop_get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436272,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581594288,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:108",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/loop.c:loop_get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581594288,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581680272,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:108",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680272,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581798384,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:110",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798384,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581870976,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:110",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581870976,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582099461,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:116",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582097040,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582146190,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:116",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_fstat"
      ],
      "caller_func": [
        "fs/init.c:init_stat",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582143776,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582171038,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:134",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_fstat"
      ],
      "caller_func": [
        "fs/init.c:init_stat",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/loop.c:loop_get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582168672,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582488334,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:152",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_fstat"
      ],
      "caller_func": [
        "fs/init.c:init_stat",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/loop.c:loop_get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582485968,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583010138,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:152",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_fstat"
      ],
      "caller_func": [
        "fs/init.c:init_stat",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/loop.c:loop_get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583007296,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583572821,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:156",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_fstat"
      ],
      "caller_func": [
        "fs/init.c:init_stat",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/loop.c:loop_get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569696,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583788901,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:162",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_fstat"
      ],
      "caller_func": [
        "fs/init.c:init_stat",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/loop.c:loop_get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583785760,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583994509,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:165",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_fstat"
      ],
      "caller_func": [
        "fs/init.c:init_stat",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/loop.c:loop_get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583991328,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493344080,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:110",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493344080,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226937156,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:110",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226937156,
      "name": "vfs_getattr",
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286888288,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:110",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286888288,
      "name": "vfs_getattr",
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273073312,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:110",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273073312,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839712,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:110",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839712,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777376,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:110",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777376,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831024,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:110",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831024,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int vfs_getattr(const struct path * path, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900416,
      "name": "vfs_getattr",
      "external": true,
      "loc": "fs/stat.c:110",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_statx",
        "fs/stat.c:vfs_statx_fd",
        "fs/ecryptfs/inode.c:ecryptfs_getattr",
        "drivers/base/devtmpfs.c:handle_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900416,
      "name": "vfs_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 request_mask</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int query_flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct path * path</code> ➡️ <code>const struct path * path</code>
</li>
</ul>
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
