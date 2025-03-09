# Function: <code>make_kgid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580016560,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:313",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:SyS_setregid",
        "kernel/sys.c:SyS_setregid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/groups.c:SyS_setgroups",
        "kernel/uid16.c:SyS_setgroups16",
        "kernel/auditfilter.c:audit_rule_change",
        "mm/shmem.c:shmem_parse_options",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:SyS_quotactl",
        "fs/proc/root.c:proc_parse_options",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:aa_may_open_profiles",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016560,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580051879,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:313",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/sys.c:SyS_setregid",
        "kernel/groups.c:SyS_setgroups",
        "kernel/uid16.c:SyS_setgroups16",
        "kernel/auditfilter.c:audit_rule_change",
        "mm/shmem.c:shmem_parse_options",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:SyS_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/root.c:proc_parse_options",
        "fs/devpts/inode.c:devpts_mount",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049024,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580091540,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:359",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/sys.c:SyS_setregid",
        "kernel/groups.c:SyS_setgroups",
        "kernel/uid16.c:SyS_setgroups16",
        "kernel/auditfilter.c:audit_rule_change",
        "mm/shmem.c:shmem_parse_options",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:SyS_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/root.c:proc_parse_options",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088528,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580097126,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:360",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/sys.c:SyS_setregid",
        "kernel/groups.c:SyS_setgroups",
        "kernel/uid16.c:SyS_setgroups16",
        "kernel/auditfilter.c:audit_rule_change",
        "mm/shmem.c:shmem_parse_options",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:SyS_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/root.c:proc_parse_options",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094176,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580150361,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:466",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/sys.c:SyS_setregid",
        "kernel/groups.c:SyS_setgroups",
        "kernel/uid16.c:SyS_setgroups16",
        "kernel/auditfilter.c:audit_rule_change",
        "mm/shmem.c:shmem_parse_options",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:SyS_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/root.c:proc_parse_options",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148032,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580210421,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:466",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:groups_from_user",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_rule_change",
        "mm/shmem.c:shmem_parse_options",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:kernel_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/root.c:proc_parse_options",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580207840,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580262581,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:466",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_rule_change",
        "mm/shmem.c:shmem_parse_options",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:kernel_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/root.c:proc_parse_options",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260096,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580313524,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:460",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_options",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/root.c:proc_reconfigure",
        "fs/proc/root.c:proc_fill_super",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_fill_super",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311152,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580362356,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:460",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/root.c:proc_reconfigure",
        "fs/proc/root.c:proc_fill_super",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359984,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580435509,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:460",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_acl_from_disk",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_fillattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "lib/kobject_uevent.c:uevent_net_broadcast_tagged",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433920,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580422549,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:460",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_acl_from_disk",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_fillattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "security/safesetid/securityfs.c:parse_policy_line",
        "security/safesetid/securityfs.c:parse_policy_line",
        "lib/kobject_uevent.c:uevent_net_broadcast_tagged",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420960,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580425417,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:461",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:new_idmap_permitted"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/stat.c:generic_fillattr",
        "fs/exec.c:begin_new_exec",
        "fs/namei.c:vfs_link",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_linkat",
        "fs/inode.c:inode_init_owner",
        "fs/inode.c:atime_needs_update",
        "fs/inode.c:inode_init_always",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_acl_from_disk",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/acl.c:fuse_set_acl",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425152,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580589173,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:477",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:new_idmap_permitted"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/stat.c:generic_fillattr",
        "fs/exec.c:begin_new_exec",
        "fs/namei.c:vfs_link",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_linkat",
        "fs/inode.c:inode_init_owner",
        "fs/inode.c:atime_needs_update",
        "fs/inode.c:inode_init_always",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_acl_from_disk",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/fuse/acl.c:fuse_set_acl",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580588896,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580791100,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:482",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:new_idmap_permitted"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/open.c:chown_common",
        "fs/stat.c:generic_fillattr",
        "fs/exec.c:bprm_fill_uid",
        "fs/namei.c:vfs_link",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_linkat",
        "fs/inode.c:inode_init_owner",
        "fs/inode.c:inode_init_owner",
        "fs/inode.c:atime_needs_update",
        "fs/inode.c:inode_init_always",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:ext4_parse_param",
        "fs/ext4/acl.c:ext4_acl_from_disk",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:aa_policy_view_capable",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790768,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581075916,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:482",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:new_idmap_permitted"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/open.c:chown_common",
        "fs/stat.c:generic_fillattr",
        "fs/exec.c:bprm_fill_uid",
        "fs/namei.c:vfs_link",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_linkat",
        "fs/inode.c:mode_strip_sgid",
        "fs/inode.c:inode_init_owner",
        "fs/inode.c:atime_needs_update",
        "fs/inode.c:inode_init_always",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_should_drop_suidgid",
        "fs/xattr.c:may_write_xattr",
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:ext4_parse_param",
        "fs/ext4/acl.c:ext4_acl_from_disk",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:aa_policy_view_capable",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581075552,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581167042,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:482",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:new_idmap_permitted"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/mnt_idmapping.c:from_vfsgid",
        "fs/mnt_idmapping.c:make_vfsgid",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:ext4_parse_param",
        "fs/ext4/acl.c:ext4_acl_from_disk",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:aa_policy_view_capable",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166640,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581271474,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:485",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:new_idmap_permitted"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/uid16.c:__do_sys_setgroups16",
        "kernel/auditfilter.c:audit_data_to_entry",
        "kernel/bpf/inode.c:bpf_parse_param",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem_quota.c:shmem_get_next_id",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/mnt_idmapping.c:from_vfsgid",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:ext4_parse_param",
        "fs/ext4/acl.c:ext4_acl_from_disk",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_fillattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "fs/efivarfs/super.c:efivarfs_parse_param",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:aa_policy_view_capable",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "io_uring/io_uring.c:__ia32_sys_io_uring_setup",
        "io_uring/io_uring.c:__x64_sys_io_uring_setup",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271136,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491623132,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:460",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:groups_from_user",
        "kernel/uid16.c:__arm64_sys_setgroups16",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/root.c:proc_reconfigure",
        "fs/proc/root.c:proc_fill_super",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491620832,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225578868,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:460",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__se_sys_setgroups",
        "kernel/uid16.c:__se_sys_setgroups16",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225576360,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284616628,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:460",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__se_sys_setgroups",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284613248,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272023382,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:460",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__se_sys_setgroups",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272020990,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580331156,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:460",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/root.c:proc_reconfigure",
        "fs/proc/root.c:proc_fill_super",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328784,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580278420,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:460",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/root.c:proc_reconfigure",
        "fs/proc/root.c:proc_fill_super",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276048,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580322404,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:460",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/root.c:proc_reconfigure",
        "fs/proc/root.c:proc_fill_super",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netfilter/nfnetlink_log.c:nfnl_log_net_init",
        "net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_pernet_init",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320032,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
kgid_t make_kgid(struct user_namespace * ns, gid_t gid)
```

```json
{
  "name": "make_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580377428,
      "name": "make_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:460",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
      ],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/uid16.c:groups16_from_user",
        "kernel/auditfilter.c:audit_data_to_entry",
        "mm/shmem.c:shmem_parse_one",
        "fs/open.c:chown_common",
        "fs/inode.c:inode_init_always",
        "fs/posix_acl.c:posix_acl_from_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_setxquota",
        "fs/quota/quota.c:quota_setquota",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/proc/root.c:proc_reconfigure",
        "fs/proc/root.c:proc_fill_super",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/proc_net.c:proc_net_ns_init",
        "fs/devpts/inode.c:parse_mount_options",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:_ext4_show_options",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/acl.c:ext4_get_acl",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fat/inode.c:parse_options",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_change_attributes_common",
        "fs/debugfs/inode.c:debugfs_parse_options",
        "fs/tracefs/inode.c:tracefs_parse_options",
        "ipc/util.c:ipc_update_perm",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/apparmor/policy.c:policy_view_capable",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/af_inet.c:inet_init_net",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/sysctl_net.c:net_ctl_set_ownership",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580374976,
      "name": "make_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
