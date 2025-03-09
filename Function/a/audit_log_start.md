# Function: <code>audit_log_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030432,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1358",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_config_change",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:__audit_seccomp",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030432,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063024,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1369",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:__audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063024,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1205
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
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580103344,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1501",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:__audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103344,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1109
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
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108912,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1685",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:__audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108912,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580161456,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1693",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:__audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161456,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 919
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1747",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230831,
      "name": "audit_log_start.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580221248,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 912
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580273761,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1744",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580283223,
      "name": "audit_log_start.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580273680,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 882
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580325456,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1744",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580324624,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 819
    },
    {
      "addr": 18446744071580333894,
      "name": "audit_log_start.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580325456,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580374256,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1746",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580373424,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 819
    },
    {
      "addr": 18446744071580382758,
      "name": "audit_log_start.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580374256,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580449839,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1821",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_log_proctitle",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_autoremove_mark_rule",
        "kernel/audit_tree.c:kill_rules",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580447808,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
    },
    {
      "addr": 18446744071580459674,
      "name": "audit_log_start.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580448624,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580438431,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1832",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_log_proctitle",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_autoremove_mark_rule",
        "kernel/audit_tree.c:kill_rules",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580436368,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
    },
    {
      "addr": 18446744071591315744,
      "name": "audit_log_start.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580437216,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580442159,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1832",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580439920,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
    },
    {
      "addr": 18446744071591257985,
      "name": "audit_log_start.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580440944,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580607007,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1869",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_put_deferred",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604768,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 997
    },
    {
      "addr": 18446744071592162517,
      "name": "audit_log_start.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580605776,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1856",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_tree.c:kill_rules",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_put_deferred",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/md/dm-audit.c:dm_audit_log_bio",
        "drivers/md/dm-audit.c:dm_audit_log_ti",
        "drivers/md/dm-audit.c:dm_audit_log_ti",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593935625,
      "name": "audit_log_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580809664,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 943
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
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581095632,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1854",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/md/dm-audit.c:dm_audit_log_bio",
        "drivers/md/dm-audit.c:dm_audit_log_ti",
        "drivers/md/dm-audit.c:dm_audit_log_ti",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095632,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581187264,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1854",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/md/dm-audit.c:dm_audit_log_bio",
        "drivers/md/dm-audit.c:dm_audit_log_ti",
        "drivers/md/dm-audit.c:dm_audit_log_ti",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581187264,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 966
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
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293456,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1872",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_uring",
        "kernel/auditsc.c:audit_log_proctitle",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_lsm_setattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/md/dm-audit.c:dm_audit_log_bio",
        "drivers/md/dm-audit.c:dm_audit_log_ti",
        "drivers/md/dm-audit.c:dm_audit_log_ti",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293456,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 966
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491638552,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1746",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491638552,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
    },
    {
      "addr": 18446603336491639472,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225591064,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1746",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225591064,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 3225591968,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284633504,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1746",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284633504,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
    },
    {
      "addr": 13835058055284634688,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272034512,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1746",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272034512,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
    },
    {
      "addr": 18446743936272035242,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580343056,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1746",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342224,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 819
    },
    {
      "addr": 18446744071580351558,
      "name": "audit_log_start.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580343056,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580290224,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1746",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289392,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 819
    },
    {
      "addr": 18446744071580298726,
      "name": "audit_log_start.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580290224,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580334304,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1746",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580333472,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 819
    },
    {
      "addr": 18446744071580342806,
      "name": "audit_log_start.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580334304,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct audit_buffer * audit_log_start(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_log_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580389552,
      "name": "audit_log_start",
      "external": true,
      "loc": "kernel/audit.c:1746",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_seccomp_actions_logged",
        "kernel/auditsc.c:audit_seccomp",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/lsm_audit.c:common_lsm_audit",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580388752,
      "name": "audit_log_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 786
    },
    {
      "addr": 18446744071580398086,
      "name": "audit_log_start.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580389552,
      "name": "audit_log_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
