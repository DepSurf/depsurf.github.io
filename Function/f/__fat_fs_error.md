# Function: <code>__fat_fs_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582134052,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:19",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_bmap",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582134052,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582350429,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:19",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350429,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441818,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:19",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441818,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582371554,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:19",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582371554,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582522338,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:19",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582522338,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582713690,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:19",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582713690,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817722,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:20",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817722,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582992698,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582992698,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583098890,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583098890,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583417850,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583417850,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591353769,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591353769,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591296691,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591296691,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592281411,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592281411,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594063748,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594063748,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585155952,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585155952,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585385088,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585385088,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585619952,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585619952,
      "name": "__fat_fs_error",
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494806184,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494806184,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228225380,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228225380,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288645448,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288645448,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274134074,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274134074,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583067626,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583067626,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583004778,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004778,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583056234,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583056234,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __fat_fs_error(struct super_block * sb, int report, const char * fmt, void (anon))
```

```json
{
  "name": "__fat_fs_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583145421,
      "name": "__fat_fs_error",
      "external": true,
      "loc": "fs/fat/misc.c:21",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_get_mapped_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_access_init",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583145421,
      "name": "__fat_fs_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
