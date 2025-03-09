# Function: <code>inode_query_iversion</code>

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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582220996,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:281",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311197,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:281",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582720976,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:281",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583381159,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:281",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582315865,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:281",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409913,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:281",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582824743,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:281",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582952077,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:281",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583500423,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:281",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582481127,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582578748,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995879,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583132224,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583687223,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582580327,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582679708,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583102071,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583238496,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583794897,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582889015,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991177,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583421287,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583565106,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584187152,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582961255,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066841,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583535159,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677461,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584305888,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582987159,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092563,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583558311,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698229,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584340224,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583323096,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583432083,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583916631,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584058485,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584728976,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583831194,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583950082,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584494923,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584649912,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585404940,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584454458,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:251",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584576882,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:251",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585162091,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:251",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585331488,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:251",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586158620,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:251",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
u64 inode_query_iversion(struct inode * inode)
```

```json
{
  "name": "inode_query_iversion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008720,
      "name": "inode_query_iversion",
      "external": true,
      "loc": "fs/libfs.c:1594",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:vfs_getattr_nosec",
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup",
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008720,
      "name": "inode_query_iversion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
u64 inode_query_iversion(struct inode * inode)
```

```json
{
  "name": "inode_query_iversion",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584221536,
      "name": "inode_query_iversion",
      "external": true,
      "loc": "fs/libfs.c:1895",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:generic_fillattr",
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup",
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584221536,
      "name": "inode_query_iversion",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494229424,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494332584,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494814176,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494961720,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495598128,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227661232,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 3227767764,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 3228233080,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3228369364,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 3228958868,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287929728,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288058152,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288657796,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288839300,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289702228,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273685188,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273768004,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274137646,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274263458,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274761024,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582549063,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582648444,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070807,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583207232,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583763633,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582486231,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582585612,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583007959,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583144384,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583700689,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582539175,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582638300,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583059415,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583191264,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583747393,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
  "name": "inode_query_iversion",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582620311,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_dx_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582721612,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583148503,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583285112,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583848337,
      "name": "inode_query_iversion",
      "external": false,
      "loc": "include/linux/iversion.h:305",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement"
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
u64 inode_query_iversion(struct inode * inode)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
