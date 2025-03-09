# Function: <code>audit_log_n_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580032848,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1550",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032848,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580065440,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1561",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/audit_fsnotify.c:audit_mark_handle_event",
        "kernel/audit_tree.c:kill_rules",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065440,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580105664,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1700",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105664,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110992,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1879",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110992,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163552,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1887",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163552,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580223392,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1940",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580223392,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275776,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1937",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275776,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580326784,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1937",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580326784,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580375584,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1939",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375584,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580451200,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:2019",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/lsm_audit.c:dump_common_audit_data",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_cb",
        "security/apparmor/ipc.c:audit_signal_cb",
        "security/apparmor/ipc.c:audit_signal_cb",
        "security/apparmor/ipc.c:audit_signal_cb",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451200,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580439824,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:2036",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/label.c:aa_label_xaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580439824,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580443920,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:2036",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/label.c:aa_label_xaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580443920,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580608768,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:2075",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/label.c:aa_label_xaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608768,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580813504,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:2057",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/label.c:aa_label_xaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580813504,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099632,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:2055",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/label.c:aa_label_xaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099632,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581191248,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:2055",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/label.c:aa_label_xaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581191248,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581297504,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:2073",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/label.c:aa_label_xaudit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581297504,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491641064,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1939",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491641064,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225593316,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1939",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225593316,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284636768,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1939",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284636768,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272036496,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1939",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272036496,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580344384,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1939",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580344384,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580291552,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1939",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580291552,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580335632,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1939",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580335632,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void audit_log_n_string(struct audit_buffer * ab, const char * string, size_t slen)
```

```json
{
  "name": "audit_log_n_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580390864,
      "name": "audit_log_n_string",
      "external": true,
      "loc": "kernel/audit.c:1939",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_n_untrustedstring",
        "kernel/auditsc.c:audit_log_execve_info",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/file.c:audit_file_mask",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580390864,
      "name": "audit_log_n_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
