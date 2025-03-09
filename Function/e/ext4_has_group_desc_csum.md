# Function: <code>ext4_has_group_desc_csum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581552073,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2704",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581558249,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2704",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602997,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2704",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581707457,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2704",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_group_desc_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730837,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2704",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581737851,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2739",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744095,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2739",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581794446,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2739",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581899804,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2739",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_group_desc_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581931206,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2739",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581825478,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2717",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831823,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2717",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581883988,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2717",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581989260,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2717",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_group_desc_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021270,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2717",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581949298,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2741",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581989174,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2741",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582029985,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2741",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582130583,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2741",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205820,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2741",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582098445,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2698",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582138601,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2698",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582177185,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2698",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582279916,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2698",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354565,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2698",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582214402,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2703",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582288219,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2703",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582321371,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2703",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582368215,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2703",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582394022,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2703",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582467826,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2703",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582547808,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2703",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582309250,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2730",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582386955,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2730",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582424939,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2730",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582467494,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2730",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582492854,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2730",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582567548,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2730",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582649120,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2730",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582475605,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2810",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582555095,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2810",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593969,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2810",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637511,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2810",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582665183,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2810",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741290,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2810",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582823279,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2810",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582574533,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655890,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582694744,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582739058,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582767183,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843570,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582926609,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_has_group_desc_csum(struct super_block * sb)
```

```json
{
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582883723,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2983",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582965236,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2983",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071583006908,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2983",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583050264,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2983",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583078407,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2983",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583146950,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2983",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583243138,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2983",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582959936,
      "name": "ext4_has_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582956610,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3155",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583042999,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3155",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079831,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3155",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126306,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3155",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583160540,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3155",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583228136,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3155",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583345064,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3155",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set"
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
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582982530,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3217",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583068873,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3217",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583104862,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3217",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583150993,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3217",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583187021,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3217",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255973,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3217",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583368017,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3217",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set"
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
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583318370,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3287",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583406945,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3287",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583445010,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3287",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583491404,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3287",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583530176,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3287",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583598647,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3287",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583723487,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3287",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set"
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
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583826005,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3250",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583922229,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3250",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583968080,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3250",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584018522,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3250",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584063909,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3250",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584135345,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3250",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584266494,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3250",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584448669,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3263",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584548256,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3263",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584595875,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3263",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584649991,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3263",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584696789,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3263",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584769377,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3263",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584917806,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3263",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584677347,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3255",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584776408,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3255",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584822166,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3255",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584873317,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3255",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584922037,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3255",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584992721,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3255",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585147177,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3255",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584909682,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3275",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585009315,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3275",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585055142,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3275",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585106174,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3275",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585141985,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3275",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585224707,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3275",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585380226,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3275",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494222152,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494308328,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494351776,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494400060,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494433480,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494517580,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494603476,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227652620,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 3227743436,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3227785772,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 3227837036,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3227868604,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 3227955764,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 3228046388,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287918748,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288027404,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288081596,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288141180,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288182720,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288285692,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288405828,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273678044,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273749442,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273781426,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273819224,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273846444,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273912000,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273979390,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582543269,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582624626,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582663480,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582707794,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582735919,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582812306,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582895345,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582480437,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582561794,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582600648,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582644962,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582673087,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749458,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582832497,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582533749,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582614482,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582653336,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582697650,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725775,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582801186,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884241,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
  "name": "ext4_has_group_desc_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582614512,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582697403,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738410,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582782034,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582810639,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582887762,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582970993,
      "name": "ext4_has_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2872",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ext4_has_group_desc_csum(struct super_block * sb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int ext4_has_group_desc_csum(struct super_block * sb)
```
</details>
</li>
</ul>
