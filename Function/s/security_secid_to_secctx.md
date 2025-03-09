# Function: <code>security_secid_to_secctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582234128,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:1154",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_secctx",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_exit",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582234128,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582452624,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:1178",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_secctx",
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452624,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582545088,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:1199",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_secctx",
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582545088,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582630304,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2117",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_secctx",
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630304,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582783696,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:1975",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582783696,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582985888,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:1303",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582985888,
      "name": "security_secid_to_secctx",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583100912,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2054",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100912,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583286224,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2073",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286224,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583391568,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2112",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391568,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int security_secid_to_secctx(struct lsmblob * blob, struct lsmcontext * cp, int display)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730032,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2338",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_lsm",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730032,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int security_secid_to_secctx(struct lsmblob * blob, struct lsmcontext * cp, int display)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583850208,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2355",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_lsm",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850208,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int security_secid_to_secctx(struct lsmblob * blob, struct lsmcontext * cp, int display)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875488,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2418",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_lsm",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875488,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int security_secid_to_secctx(struct lsmblob * blob, struct lsmcontext * cp, int display)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2426",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_lsm",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592293468,
      "name": "security_secid_to_secctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584240832,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int security_secid_to_secctx(struct lsmblob * blob, struct lsmcontext * cp, int ilsm)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2451",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_receive_msg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594075494,
      "name": "security_secid_to_secctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584847264,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int security_secid_to_secctx(struct lsmblob * blob, struct lsmcontext * cp, int ilsm)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2431",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_receive_msg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596094048,
      "name": "security_secid_to_secctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585549712,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int security_secid_to_secctx(struct lsmblob * blob, struct lsmcontext * cp, int ilsm)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:4097",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_receive_msg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596617384,
      "name": "security_secid_to_secctx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585780336,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int security_secid_to_secctx(u32 secid, struct lsmcontext * cp)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586021088,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:4265",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586021088,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495142560,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2112",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495142560,
      "name": "security_secid_to_secctx",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228530328,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2112",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228530328,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289061120,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2112",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289061120,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274391904,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2112",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274391904,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583360304,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2112",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360304,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583297408,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2112",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583297408,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583344080,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2112",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netfilter/nf_conntrack_standalone.c:ct_seq_show",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_build_size",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344080,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int security_secid_to_secctx(u32 secid, char * * secdata, u32 * seclen)
```

```json
{
  "name": "security_secid_to_secctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583439264,
      "name": "security_secid_to_secctx",
      "external": true,
      "loc": "security/security.c:2112",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439264,
      "name": "security_secid_to_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob * blob</code>
</li>
<li>
<b>Param added. </b>
<code>struct lsmcontext * cp</code>
</li>
<li>
<b>Param added. </b>
<code>int display</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 secid</code>
</li>
<li>
<b>Param removed. </b>
<code>char * * secdata</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 * seclen</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int ilsm</code>
</li>
<li>
<b>Param removed. </b>
<code>int display</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 secid</code>
</li>
<li>
<b>Param removed. </b>
<code>struct lsmblob * blob</code>
</li>
<li>
<b>Param removed. </b>
<code>int ilsm</code>
</li>
</ul>
</details>
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
