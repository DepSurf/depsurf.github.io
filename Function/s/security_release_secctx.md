# Function: <code>security_release_secctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582234336,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:1168",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_secctx",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_pid_context",
        "kernel/auditsc.c:audit_log_exit",
        "fs/xattr.c:xattr_getsecurity",
        "fs/kernfs/inode.c:kernfs_iop_setxattr",
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
      "addr": 18446744071582234336,
      "name": "security_release_secctx",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582452832,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:1192",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_secctx",
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "fs/xattr.c:xattr_getsecurity",
        "fs/kernfs/inode.c:kernfs_iop_setxattr",
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
      "addr": 18446744071582452832,
      "name": "security_release_secctx",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582545296,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:1213",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_secctx",
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "fs/xattr.c:xattr_getsecurity",
        "fs/kernfs/inode.c:kernfs_security_xattr_set",
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
      "addr": 18446744071582545296,
      "name": "security_release_secctx",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582632864,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2131",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_secctx",
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "fs/xattr.c:xattr_getsecurity",
        "fs/kernfs/inode.c:kernfs_security_xattr_set",
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
      "addr": 18446744071582632864,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582786512,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:1989",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "fs/kernfs/inode.c:kernfs_security_xattr_set",
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
      "addr": 18446744071582786512,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582986080,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:1317",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "fs/kernfs/inode.c:kernfs_security_xattr_set",
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
      "addr": 18446744071582986080,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097664,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2068",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_log_name",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/auditsc.c:audit_log_pid_context",
        "fs/kernfs/inode.c:kernfs_security_xattr_set",
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
      "addr": 18446744071583097664,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583280816,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2087",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071583280816,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583386768,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2126",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071583386768,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void security_release_secctx(struct lsmcontext * cp)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583729856,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2397",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071583729856,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void security_release_secctx(struct lsmcontext * cp)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583850032,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2414",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071583850032,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void security_release_secctx(struct lsmcontext * cp)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875312,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2477",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071583875312,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void security_release_secctx(struct lsmcontext * cp)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584239808,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2485",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071584239808,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void security_release_secctx(struct lsmcontext * cp)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584847056,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2515",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fuse/dir.c:get_security_context",
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
      "addr": 18446744071584847056,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void security_release_secctx(struct lsmcontext * cp)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585549472,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2495",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fuse/dir.c:get_security_context",
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
      "addr": 18446744071585549472,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void security_release_secctx(struct lsmcontext * cp)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585780096,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:4177",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071585780096,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void security_release_secctx(struct lsmcontext * cp)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586027824,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:4341",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_log_subject_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071586027824,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495136488,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2126",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446603336495136488,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228524452,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2126",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 3228524452,
      "name": "security_release_secctx",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289050096,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2126",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 13835058055289050096,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274387378,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2126",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446743936274387378,
      "name": "security_release_secctx",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583355504,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2126",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071583355504,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583292608,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2126",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071583292608,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583339280,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2126",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netfilter/nf_conntrack_standalone.c:ct_seq_show",
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
      "addr": 18446744071583339280,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void security_release_secctx(char * secdata, u32 seclen)
```

```json
{
  "name": "security_release_secctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583434464,
      "name": "security_release_secctx",
      "external": true,
      "loc": "security/security.c:2126",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071583434464,
      "name": "security_release_secctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<code>struct lsmcontext * cp</code>
</li>
<li>
<b>Param removed. </b>
<code>char * secdata</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 seclen</code>
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
