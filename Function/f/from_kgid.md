# Function: <code>from_kgid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580016688,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:332",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/ptrace.c:ptrace_has_cap",
        "kernel/ptrace.c:ptrace_has_cap",
        "kernel/ptrace.c:ptrace_has_cap",
        "kernel/audit.c:audit_log_name",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_task",
        "fs/attr.c:inode_change_ok",
        "fs/attr.c:inode_change_ok",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/coredump.c:do_coredump",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016688,
      "name": "from_kgid",
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580050493,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:332",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/ptrace.c:ptrace_has_cap",
        "kernel/ptrace.c:ptrace_has_cap",
        "kernel/ptrace.c:ptrace_has_cap",
        "kernel/audit.c:audit_log_name",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049152,
      "name": "from_kgid",
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580090186,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:378",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_name",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088656,
      "name": "from_kgid",
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580095834,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:379",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_name",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094304,
      "name": "from_kgid",
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580148680,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:485",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_name",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148368,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580208474,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:485",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_name",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208176,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580260730,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:485",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_name",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260432,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580311755,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:479",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311456,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580360587,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:479",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360288,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580433515,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:479",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:bprm_fill_uid",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:may_o_create",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:format_corename",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433216,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580420555,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:479",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:bprm_fill_uid",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:may_o_create",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:format_corename",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420256,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580424747,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:480",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/open.c:chown_common",
        "fs/exec.c:begin_new_exec",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424448,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580588491,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:496",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/open.c:chown_common",
        "fs/exec.c:begin_new_exec",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/quota/kqid.c:from_kqid",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580588192,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580790314,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:501",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/open.c:chown_common",
        "fs/open.c:chown_common",
        "fs/stat.c:generic_fillattr",
        "fs/exec.c:bprm_fill_uid",
        "fs/exec.c:bprm_fill_uid",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_linkat",
        "fs/inode.c:inode_init_owner",
        "fs/inode.c:inode_init_owner",
        "fs/inode.c:atime_needs_update",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/quota/kqid.c:from_kqid",
        "fs/ext4/inode.c:ext4_fill_raw_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/fat/file.c:fat_setattr",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789984,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581075034,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:501",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/open.c:chown_common",
        "fs/stat.c:generic_fillattr",
        "fs/exec.c:bprm_fill_uid",
        "fs/exec.c:bprm_fill_uid",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_linkat",
        "fs/inode.c:mode_strip_sgid",
        "fs/inode.c:inode_init_owner",
        "fs/inode.c:atime_needs_update",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_should_drop_suidgid",
        "fs/xattr.c:may_write_xattr",
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/kqid.c:from_kqid",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_fill_raw_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074624,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581165959,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:501",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/shmem.c:shmem_parse_one",
        "fs/exec.c:begin_new_exec",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj",
        "fs/mnt_idmapping.c:from_vfsgid",
        "fs/mnt_idmapping.c:make_vfsgid",
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/quota/kqid.c:from_kqid",
        "fs/ext4/inode.c:ext4_fill_raw_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165552,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581277079,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:504",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/bpf/inode.c:bpf_parse_param",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/shmem.c:shmem_parse_one",
        "fs/exec.c:begin_new_exec",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj",
        "fs/mnt_idmapping.c:make_vfsgid",
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/quota/kqid.c:from_kqid",
        "fs/ext4/inode.c:ext4_fill_raw_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275824,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491621736,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:479",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491621320,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225577104,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:479",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:format_corename",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225576776,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284614292,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:479",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284613808,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272021798,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:479",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272021398,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580329387,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:479",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329088,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580276651,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:479",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276352,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580320635,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:479",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320336,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
gid_t from_kgid(struct user_namespace * targ, kgid_t kgid)
```

```json
{
  "name": "from_kgid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580375579,
      "name": "from_kgid",
      "external": true,
      "loc": "kernel/user_namespace.c:479",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/audit.c:tomoyo_print_header",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375280,
      "name": "from_kgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
