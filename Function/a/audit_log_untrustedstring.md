# Function: <code>audit_log_untrustedstring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580033296,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:1624",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_task",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/net.c:audit_unix_addr",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_log_string",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033296,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580067627,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:1635",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/net.c:audit_unix_addr",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_log_string",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065856,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580107851,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:1774",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/net.c:audit_unix_addr",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_log_string",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106080,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111424,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:1953",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/net.c:audit_unix_addr",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_log_string_op",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111424,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163984,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:1961",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/lsm_audit.c:common_lsm_audit",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/net.c:audit_unix_addr",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_log_string_op",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163984,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580223824,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2014",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/ima/ima_policy.c:ima_log_string_op",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580223824,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276208,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2011",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276208,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580327184,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2011",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327184,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580375984,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2013",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375984,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580451664,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2093",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_autoremove_mark_rule",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451664,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580440240,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2110",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_autoremove_mark_rule",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580440240,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580444320,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2110",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580444320,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580609168,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2149",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609168,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580814016,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2131",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814016,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581100192,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2129",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100192,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581191808,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2129",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581191808,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581298064,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2147",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_watch.c:audit_remove_parent_watches",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/task.c:audit_ns_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298064,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491641656,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2013",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491641656,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225593800,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2013",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225593800,
      "name": "audit_log_untrustedstring",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284637504,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2013",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284637504,
      "name": "audit_log_untrustedstring",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272037980,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2013",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272037002,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580344784,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2013",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580344784,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580291952,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2013",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580291952,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336032,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2013",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336032,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void audit_log_untrustedstring(struct audit_buffer * ab, const char * string)
```

```json
{
  "name": "audit_log_untrustedstring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580391264,
      "name": "audit_log_untrustedstring",
      "external": true,
      "loc": "kernel/audit.c:2013",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_key",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/smack/smack_access.c:smack_log_callback",
        "security/smack/smack_access.c:smack_log_callback",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/capability.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/policy_unpack.c:audit_cb",
        "security/apparmor/file.c:file_audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/apparmor/mount.c:audit_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/ima/ima_api.c:ima_audit_measurement",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/tty/tty_audit.c:tty_audit_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391264,
      "name": "audit_log_untrustedstring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
