# Function: <code>audit_log_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029152,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:1960",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_config_change",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029152,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580061728,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:1981",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061728,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580102208,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2120",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102208,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580107776,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2287",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107776,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580160448,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2295",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580160448,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220240,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2337",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220240,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580272688,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2334",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580272688,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580323600,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2299",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580323600,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580372400,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2301",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580372400,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580446640,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2453",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580446640,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580435232,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2470",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580435232,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580438768,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2470",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580438768,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580603616,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2509",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603616,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580811596,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2574",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_config_change"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/md/dm-audit.c:dm_audit_log_bio",
        "drivers/md/dm-audit.c:dm_audit_log_ti",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580807664,
      "name": "audit_log_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    },
    {
      "addr": 18446744071580808016,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581097660,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2572",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_config_change"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/md/dm-audit.c:dm_audit_log_bio",
        "drivers/md/dm-audit.c:dm_audit_log_ti",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093520,
      "name": "audit_log_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581093888,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581189276,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2572",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_config_change"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/md/dm-audit.c:dm_audit_log_bio",
        "drivers/md/dm-audit.c:dm_audit_log_ti",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581185120,
      "name": "audit_log_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581185488,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581295484,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2594",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_config_change"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_path_denied",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/md/dm-audit.c:dm_audit_log_bio",
        "drivers/md/dm-audit.c:dm_audit_log_ti",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291296,
      "name": "audit_log_end.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581291664,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491637368,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2301",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491637368,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225590040,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2301",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225590040,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284632080,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2301",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284632080,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272033638,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2301",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272033638,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580341200,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2301",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580341200,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288368,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2301",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288368,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580332448,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2301",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580332448,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void audit_log_end(struct audit_buffer * ab)
```

```json
{
  "name": "audit_log_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580387728,
      "name": "audit_log_end",
      "external": true,
      "loc": "kernel/audit.c:2301",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_link_denied",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
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
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_audit_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_acceptflg_set",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387728,
      "name": "audit_log_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
