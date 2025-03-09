# Function: <code>_fat_msg</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void _fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "_fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594063576,
      "name": "_fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:54",
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
      "addr": 18446744071594063576,
      "name": "_fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void _fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "_fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585155776,
      "name": "_fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:54",
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
      "addr": 18446744071585155776,
      "name": "_fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void _fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "_fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585384912,
      "name": "_fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:54",
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
      "addr": 18446744071585384912,
      "name": "_fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void _fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "_fat_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585619776,
      "name": "_fat_msg",
      "external": true,
      "loc": "fs/fat/misc.c:54",
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
      "addr": 18446744071585619776,
      "name": "_fat_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void _fat_msg(struct super_block * sb, const char * level, const char * fmt, void (anon))
```
</details>
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
