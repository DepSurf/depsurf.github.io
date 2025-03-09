# Function: <code>fat_truncate_time</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582815984,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:284",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582815984,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990992,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:285",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990992,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097184,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:285",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097184,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583416112,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:293",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416112,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583530544,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:293",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583530544,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583553696,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:293",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583553696,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583912224,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:296",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912224,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584489808,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:314",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584489808,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585155264,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:314",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585155264,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585384400,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:314",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585384400,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585619296,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:314",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585619296,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494804120,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:285",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494804120,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228223348,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:285",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228223348,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288642880,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:285",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288642880,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274132438,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:285",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274132438,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583065920,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:285",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583065920,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583003072,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:285",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583003072,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583054528,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:285",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583054528,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```

```json
{
  "name": "fat_truncate_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583143728,
      "name": "fat_truncate_time",
      "external": true,
      "loc": "fs/fat/misc.c:285",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583143728,
      "name": "fat_truncate_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int fat_truncate_time(struct inode * inode, struct timespec64 * now, int flags)
```
</details>
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
