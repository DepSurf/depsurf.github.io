# Function: <code>from_vfsgid</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "from_vfsgid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583521463,
      "name": "from_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:323",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:chown_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583613120,
      "name": "from_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:323",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583702775,
      "name": "from_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:323",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:inode_init_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583718324,
      "name": "from_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:323",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584176846,
      "name": "from_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:323",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:vfs_set_acl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584252188,
      "name": "from_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:323",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584634365,
      "name": "from_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:323",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585138005,
      "name": "from_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:323",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_setattr"
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
kgid_t from_vfsgid(struct mnt_idmap * idmap, struct user_namespace * fs_userns, vfsgid_t vfsgid)
```

```json
{
  "name": "from_vfsgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584115408,
      "name": "from_vfsgid",
      "external": true,
      "loc": "fs/mnt_idmapping.c:192",
      "file": "fs/mnt_idmapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_copy",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115408,
      "name": "from_vfsgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
kgid_t from_vfsgid(struct mnt_idmap * idmap, struct user_namespace * fs_userns, vfsgid_t vfsgid)
```

```json
{
  "name": "from_vfsgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584331696,
      "name": "from_vfsgid",
      "external": true,
      "loc": "fs/mnt_idmapping.c:163",
      "file": "fs/mnt_idmapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:chown_common",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_copy",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331696,
      "name": "from_vfsgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
kgid_t from_vfsgid(struct mnt_idmap * idmap, struct user_namespace * fs_userns, vfsgid_t vfsgid)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
