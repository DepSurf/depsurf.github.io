# Function: <code>fat_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582133924,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:46",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133924,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582350301,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:46",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350301,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441690,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:46",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441690,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582371426,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:46",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582371426,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582522210,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:46",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582522210,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582713560,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:46",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582713560,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817592,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:47",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817592,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582992568,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582992568,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583098760,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583098760,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583417720,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:uni16_to_x8",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_rebuild_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583417720,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591353639,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:uni16_to_x8",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_rebuild_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591353639,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591296561,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_rebuild_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591296561,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592281281,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_static_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:fat_read_bpb",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_rebuild_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592281281,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494806028,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494806028,
      "name": "fat_msg",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228225252,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228225252,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288645284,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288645284,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274133970,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274133970,
      "name": "fat_msg",
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583067496,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583067496,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583004648,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004648,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583056104,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583056104,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583145291,
      "name": "fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:48",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:fat_search_long",
        "fs/fat/dir.c:fat_parse_short",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:parse_options",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/misc.c:__fat_fs_error",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583145291,
      "name": "fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```
</details>
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
