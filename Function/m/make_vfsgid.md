# Function: <code>make_vfsgid</code>

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
  "name": "make_vfsgid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579871373,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:privileged_wrt_inode_uidgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583569119,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:generic_fillattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583577847,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:bprm_fill_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583618477,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_link",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_linkat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583705099,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:mode_strip_sgid",
        "fs/inode.c:atime_needs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583718892,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_should_drop_suidgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583782088,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:may_write_xattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584183660,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584252098,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584633650,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585137923,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585327354,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "fs/fuse/acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/acl.c:fuse_set_acl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164959,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_match_rules"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586193245,
      "name": "make_vfsgid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:230",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
vfsgid_t make_vfsgid(struct mnt_idmap * idmap, struct user_namespace * fs_userns, kgid_t kgid)
```

```json
{
  "name": "make_vfsgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584115296,
      "name": "make_vfsgid",
      "external": true,
      "loc": "fs/mnt_idmapping.c:135",
      "file": "fs/mnt_idmapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "fs/stat.c:generic_fillattr",
        "fs/exec.c:begin_new_exec",
        "fs/namei.c:vfs_link",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_linkat",
        "fs/inode.c:mode_strip_sgid",
        "fs/inode.c:atime_needs_update",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_should_drop_suidgid",
        "fs/xattr.c:may_write_xattr",
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fuse/acl.c:fuse_set_acl",
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115296,
      "name": "make_vfsgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
vfsgid_t make_vfsgid(struct mnt_idmap * idmap, struct user_namespace * fs_userns, kgid_t kgid)
```

```json
{
  "name": "make_vfsgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584331504,
      "name": "make_vfsgid",
      "external": true,
      "loc": "fs/mnt_idmapping.c:108",
      "file": "fs/mnt_idmapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_setattr",
        "fs/stat.c:generic_fillattr",
        "fs/exec.c:begin_new_exec",
        "fs/namei.c:vfs_link",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_linkat",
        "fs/inode.c:mode_strip_sgid",
        "fs/inode.c:atime_needs_update",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_should_drop_suidgid",
        "fs/xattr.c:may_write_xattr",
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fuse/acl.c:fuse_set_acl",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331504,
      "name": "make_vfsgid",
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
vfsgid_t make_vfsgid(struct mnt_idmap * idmap, struct user_namespace * fs_userns, kgid_t kgid)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
