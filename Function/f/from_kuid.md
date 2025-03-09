# Function: <code>from_kuid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580016304,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:264",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:no_context",
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/ptrace.c:ptrace_has_cap",
        "kernel/ptrace.c:ptrace_has_cap",
        "kernel/ptrace.c:ptrace_has_cap",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "mm/oom_kill.c:dump_header",
        "fs/fcntl.c:SyS_fcntl",
        "fs/fcntl.c:SyS_fcntl",
        "fs/attr.c:inode_change_ok",
        "fs/attr.c:inode_change_ok",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/selinux/selinuxfs.c:sel_write_disable",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016304,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580050285,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:264",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:no_context",
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/ptrace.c:ptrace_has_cap",
        "kernel/ptrace.c:ptrace_has_cap",
        "kernel/ptrace.c:ptrace_has_cap",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/fcntl.c:SyS_fcntl",
        "fs/fcntl.c:SyS_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_loginuid_read",
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
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_disable",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048768,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580089994,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:310",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:no_context",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/fcntl.c:SyS_fcntl",
        "fs/fcntl.c:SyS_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_loginuid_read",
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
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_disable",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088272,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580095642,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:311",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:no_context",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:dump_header",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_loginuid_read",
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
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580093920,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580148568,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:417",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:no_context",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_loginuid_read",
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
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148320,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580208362,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:417",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:no_context",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208128,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580260618,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:417",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:no_context",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:dump_header",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/tomoyo.c:tomoyo_path_chown",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260384,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580311643,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:411",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:no_context",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311408,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580360475,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:411",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:no_context",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360240,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580433403,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:411",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:show_fault_oops",
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:bprm_fill_uid",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:may_o_create",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:format_corename",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:proc_key_users_next",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/persistent.c:key_get_persistent",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433168,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580420443,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:411",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:show_fault_oops",
        "kernel/capability.c:capable_wrt_inode_uidgid",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:bprm_fill_uid",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:may_o_create",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:format_corename",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:proc_key_users_next",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/persistent.c:key_get_persistent",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420208,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580424635,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:412",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:show_fault_oops",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
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
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/inode.c:inode_owner_or_capable",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:proc_key_users_next",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:key_get_persistent",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424400,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580588379,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:428",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:show_fault_oops",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
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
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/inode.c:inode_owner_or_capable",
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/quota/kqid.c:from_kqid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:proc_key_users_next",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:key_get_persistent",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580588144,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580790186,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:433",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:show_fault_oops",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "fs/open.c:chown_common",
        "fs/stat.c:generic_fillattr",
        "fs/exec.c:bprm_fill_uid",
        "fs/exec.c:bprm_fill_uid",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_open",
        "fs/namei.c:do_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:pick_link",
        "fs/namei.c:may_linkat",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/inode.c:inode_owner_or_capable",
        "fs/inode.c:inode_owner_or_capable",
        "fs/inode.c:inode_init_owner",
        "fs/inode.c:atime_needs_update",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/quota/kqid.c:from_kqid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_fill_raw_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:proc_key_users_next",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:key_get_persistent",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/ipc.c:audit_mqueue_cb",
        "security/apparmor/ipc.c:audit_mqueue_cb",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789904,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581074890,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:433",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:show_fault_oops",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "fs/open.c:chown_common",
        "fs/open.c:chown_common",
        "fs/stat.c:generic_fillattr",
        "fs/exec.c:bprm_fill_uid",
        "fs/exec.c:bprm_fill_uid",
        "fs/namei.c:vfs_link",
        "fs/namei.c:do_open",
        "fs/namei.c:do_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:may_delete",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:pick_link",
        "fs/namei.c:may_linkat",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/inode.c:inode_owner_or_capable",
        "fs/inode.c:inode_owner_or_capable",
        "fs/inode.c:inode_init_owner",
        "fs/inode.c:atime_needs_update",
        "fs/attr.c:notify_change",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:may_write_xattr",
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:do_coredump",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/kqid.c:from_kqid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/ialloc.c:__ext4_new_inode",
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
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:proc_key_users_next",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:key_get_persistent",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/ipc.c:audit_mqueue_cb",
        "security/apparmor/ipc.c:audit_mqueue_cb",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/notify.c:build_unotif",
        "security/apparmor/notify.c:build_unotif",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074512,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581165815,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:433",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:show_fault_oops",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "mm/shmem.c:shmem_parse_one",
        "fs/exec.c:begin_new_exec",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/inode.c:inode_owner_or_capable",
        "fs/mnt_idmapping.c:from_vfsuid",
        "fs/mnt_idmapping.c:make_vfsuid",
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/quota/kqid.c:from_kqid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_fill_raw_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:proc_key_users_next",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:key_get_persistent",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/ipc.c:audit_mqueue_cb",
        "security/apparmor/ipc.c:audit_mqueue_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/notify.c:build_v3_unotif",
        "security/apparmor/notify.c:build_v3_unotif",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165440,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581275719,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:436",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:show_fault_oops",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/inode.c:bpf_parse_param",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_parse_one",
        "fs/exec.c:begin_new_exec",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/inode.c:inode_owner_or_capable",
        "fs/mnt_idmapping.c:make_vfsuid",
        "fs/posix_acl.c:do_get_acl",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/quota/kqid.c:from_kqid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_fill_raw_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:iattr_to_fattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:proc_key_users_next",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:key_get_persistent",
        "security/commoncap.c:get_vfs_caps_from_disk",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/ipc.c:audit_mqueue_cb",
        "security/apparmor/ipc.c:audit_mqueue_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/notify.c:build_v3_unotif",
        "security/apparmor/notify.c:build_v3_unotif",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275568,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491621616,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:411",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491621192,
      "name": "from_kuid",
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225576984,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:411",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/inode.c:inode_owner_or_capable",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/coredump.c:format_corename",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225576704,
      "name": "from_kuid",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284614116,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:411",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/powerpc/mm/fault.c:__do_page_fault",
        "arch/powerpc/mm/fault.c:__do_page_fault",
        "arch/powerpc/mm/fault.c:__do_page_fault",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284613696,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272021696,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:411",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:__se_sys_fcntl",
        "fs/fcntl.c:__se_sys_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272021276,
      "name": "from_kuid",
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580329275,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:411",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:no_context",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329040,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580276539,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:411",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:no_context",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276304,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580320523,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:411",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:no_context",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320288,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
uid_t from_kuid(struct user_namespace * targ, kuid_t kuid)
```

```json
{
  "name": "from_kuid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580375467,
      "name": "from_kuid",
      "external": true,
      "loc": "kernel/user_namespace.c:411",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:no_context",
        "kernel/capability.c:privileged_wrt_inode_uidgid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_session_info",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/bpf/helpers.c:bpf_get_current_uid_gid",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "fs/exec.c:prepare_binprm",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/attr.c:notify_change",
        "fs/posix_acl.c:posix_acl_to_xattr",
        "fs/posix_acl.c:posix_acl_fix_xattr_userns",
        "fs/posix_acl.c:posix_acl_valid",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time",
        "fs/ext4/super.c:trace_event_raw_event_ext4_free_inode",
        "fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:__ext4_set_acl",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon",
        "fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dir.c:fuse_do_setattr",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/process_keys.c:get_user_session_keyring_rcu",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/proc.c:__key_user_next",
        "security/keys/proc.c:proc_keys_next",
        "security/keys/proc.c:proc_keys_start",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/commoncap.c:cap_convert_nscap",
        "security/commoncap.c:cap_inode_getsecurity",
        "security/commoncap.c:rootid_owns_currentns",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/ss/services.c:security_set_bools",
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
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "security/integrity/evm/evm_crypto.c:hmac_add_misc",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/base/core.c:dev_uevent",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/core/dev.c:__dev_set_promiscuity",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375232,
      "name": "from_kuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
