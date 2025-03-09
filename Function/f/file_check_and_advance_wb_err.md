# Function: <code>file_check_and_advance_wb_err</code>

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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580639312,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:611",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580639312,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580721904,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:705",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/fuse/file.c:fuse_fsync_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721904,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857248,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:705",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/fuse/file.c:fuse_fsync_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857248,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580925888,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:682",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925888,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021888,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:723",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021888,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077136,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:732",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077136,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581264624,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:710",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264624,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581307120,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:711",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307120,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581328160,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:742",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328160,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581577008,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:760",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577008,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924176,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:729",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924176,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582361600,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:724",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582361600,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582564928,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:731",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/buffer.c:generic_buffers_fsync_noflush",
        "fs/buffer.c:generic_buffers_fsync_noflush",
        "fs/buffer.c:generic_buffers_fsync_noflush",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582564928,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582735792,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:726",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/buffer.c:generic_buffers_fsync_noflush",
        "fs/buffer.c:generic_buffers_fsync_noflush",
        "fs/buffer.c:generic_buffers_fsync_noflush",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582735792,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492446512,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:732",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492446512,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226316428,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:732",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226316428,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285712960,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:732",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285712960,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272516766,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:732",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272516766,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581045984,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:732",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045984,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993264,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:732",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993264,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037184,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:732",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037184,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int file_check_and_advance_wb_err(struct file * file)
```

```json
{
  "name": "file_check_and_advance_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581098768,
      "name": "file_check_and_advance_wb_err",
      "external": true,
      "loc": "mm/filemap.c:732",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:file_fdatawait_range",
        "fs/libfs.c:__generic_file_fsync",
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098768,
      "name": "file_check_and_advance_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int file_check_and_advance_wb_err(struct file * file)
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
