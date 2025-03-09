# Function: <code>inode_maybe_inc_iversion</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581698466,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:generic_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582303537,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582340241,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582439512,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582678982,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582707044,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582722030,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581784818,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:generic_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402161,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582439360,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582538968,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582780852,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582809923,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582816388,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582826207,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582900104,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:174",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581902994,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:generic_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582568291,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582608810,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582710969,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582955012,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582985004,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991394,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583000302,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583077944,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581975234,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:generic_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582669235,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582709722,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582813305,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583059892,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583091437,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583097586,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583106494,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583182744,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582208688,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582980355,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583021114,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583123257,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583379314,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583408471,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_read_root",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583416550,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583426763,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583508168,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582256160,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583056931,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583096756,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583202697,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583495202,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583524007,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_read_root",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583530982,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583540635,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583617080,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582281793,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583083014,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121780,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583230464,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583516914,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583547159,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_read_root",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583554173,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583563739,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583639736,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582599793,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583422048,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583462612,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583576480,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583872562,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583905108,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_read_root",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583912701,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583922299,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583998616,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583132947,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583938757,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583985891,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584119946,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584447435,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584483688,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_read_root",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584490248,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584501479,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584583224,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool inode_maybe_inc_iversion(struct inode * inode, bool force)
```

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583791968,
      "name": "inode_maybe_inc_iversion",
      "external": true,
      "loc": "fs/libfs.c:1558",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fileattr_set",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_unlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "fs/posix_acl.c:simple_set_acl",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583791968,
      "name": "inode_maybe_inc_iversion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool inode_maybe_inc_iversion(struct inode * inode, bool force)
```

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008624,
      "name": "inode_maybe_inc_iversion",
      "external": true,
      "loc": "fs/libfs.c:1553",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fileattr_set",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_unlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "fs/posix_acl.c:simple_set_acl",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008624,
      "name": "inode_maybe_inc_iversion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool inode_maybe_inc_iversion(struct inode * inode, bool force)
```

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584221440,
      "name": "inode_maybe_inc_iversion",
      "external": true,
      "loc": "fs/libfs.c:1854",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_xattr_handler_set",
        "mm/shmem.c:shmem_xattr_handler_set",
        "mm/shmem.c:shmem_fileattr_set",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_unlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "fs/inode.c:inode_update_timestamps",
        "fs/posix_acl.c:simple_set_acl",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584221440,
      "name": "inode_maybe_inc_iversion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493484212,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:generic_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494322100,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494386724,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494483124,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494767344,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494798648,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494804576,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494815672,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494901752,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227048748,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:generic_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 3227758276,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 3227801684,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 3227920344,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 3228184452,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 3228218548,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 3228223880,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228234884,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3228322292,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287047312,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:generic_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288044928,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288099700,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288245040,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288590628,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288636776,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288643552,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288655216,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288766160,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273158690,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:generic_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273761496,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273794814,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273885670,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274100870,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274128098,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274132752,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274141838,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274212388,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581943970,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:generic_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637971,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582678458,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582782041,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583028628,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583060173,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066322,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583075230,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583151480,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581881538,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:generic_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582575139,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582615626,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582719209,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582965780,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997325,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583003474,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583012382,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583088632,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581935282,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:generic_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582627827,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582668314,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770953,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017236,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583048781,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583054930,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583063838,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583135512,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_maybe_inc_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582006722,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:generic_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582710963,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582752090,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857193,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583106420,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583138845,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583144130,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583153118,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583229192,
      "name": "inode_maybe_inc_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:198",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool inode_maybe_inc_iversion(struct inode * inode, bool force)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
