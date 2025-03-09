# Function: <code>make_vfsuid</code>

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
  "name": "make_vfsuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579871282,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:privileged_wrt_inode_uidgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583569048,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:generic_fillattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583577773,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:bprm_fill_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583618398,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_open",
        "fs/namei.c:do_open",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:pick_link",
        "fs/namei.c:may_linkat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583704267,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:inode_owner_or_capable",
        "fs/inode.c:atime_needs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583718229,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583782026,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:may_write_xattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583894865,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584183789,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584191638,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584251920,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584633201,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585137807,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585537460,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_getsecurity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585964744,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586023722,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586041710,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:__file_path_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164849,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_match_rules"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586193169,
      "name": "make_vfsuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:192",
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
vfsuid_t make_vfsuid(struct mnt_idmap * idmap, struct user_namespace * fs_userns, kuid_t kuid)
```

```json
{
  "name": "make_vfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584115056,
      "name": "make_vfsuid",
      "external": true,
      "loc": "fs/mnt_idmapping.c:96",
      "file": "fs/mnt_idmapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "fs/stat.c:generic_fillattr",
        "fs/exec.c:begin_new_exec",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_open",
        "fs/namei.c:do_open",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:pick_link",
        "fs/namei.c:may_linkat",
        "fs/inode.c:inode_owner_or_capable",
        "fs/inode.c:atime_needs_update",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:may_write_xattr",
        "fs/locks.c:generic_setlease",
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/coredump.c:do_coredump",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/file.c:fat_setattr",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond",
        "security/apparmor/file.c:__file_path_perm",
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115056,
      "name": "make_vfsuid",
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
vfsuid_t make_vfsuid(struct mnt_idmap * idmap, struct user_namespace * fs_userns, kuid_t kuid)
```

```json
{
  "name": "make_vfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584331408,
      "name": "make_vfsuid",
      "external": true,
      "loc": "fs/mnt_idmapping.c:70",
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
        "fs/namei.c:do_open",
        "fs/namei.c:do_open",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:pick_link",
        "fs/namei.c:may_linkat",
        "fs/inode.c:inode_owner_or_capable",
        "fs/inode.c:atime_needs_update",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:may_write_xattr",
        "fs/locks.c:generic_setlease",
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/coredump.c:do_coredump",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/file.c:fat_setattr",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond",
        "security/apparmor/file.c:__file_path_perm",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331408,
      "name": "make_vfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
vfsuid_t make_vfsuid(struct mnt_idmap * idmap, struct user_namespace * fs_userns, kuid_t kuid)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
