# Function: <code>tomoyo_path_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582447168,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:785",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582447168,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669152,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:785",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669152,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582762208,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:785",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582762208,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582854672,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:785",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582854672,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011616,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:786",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011616,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583212288,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:786",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583212288,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583329232,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:786",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329232,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583516656,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583516656,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583622544,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583622544,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583979552,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583979552,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584099360,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584099360,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584126960,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126960,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584508896,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584508896,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585146544,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585146544,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585871888,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_file_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585871888,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586103760,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_file_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586103760,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586353056,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_file_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586353056,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495406896,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495406896,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228778092,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228778092,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289440000,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289440000,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274605410,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274605410,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583591280,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583591280,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583528336,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528336,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583575056,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583575056,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int tomoyo_path_perm(const u8 operation, const struct path * path, const char * target)
```

```json
{
  "name": "tomoyo_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672224,
      "name": "tomoyo_path_perm",
      "external": true,
      "loc": "security/tomoyo/file.c:803",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/tomoyo.c:tomoyo_sb_umount",
        "security/tomoyo/tomoyo.c:tomoyo_path_chroot",
        "security/tomoyo/tomoyo.c:tomoyo_path_symlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_rmdir",
        "security/tomoyo/tomoyo.c:tomoyo_path_unlink",
        "security/tomoyo/tomoyo.c:tomoyo_path_truncate",
        "security/tomoyo/tomoyo.c:tomoyo_inode_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672224,
      "name": "tomoyo_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
