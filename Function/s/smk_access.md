# Function: <code>smk_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582394320,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:125",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_file_open",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582394320,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582615968,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:125",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_open",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615968,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582709120,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:120",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_open",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582709120,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582802224,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:120",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582802224,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582958624,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:120",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582958624,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583158864,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:120",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583158864,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583275072,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:120",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275072,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583462480,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:116",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583462480,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583568432,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:116",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583568432,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583920528,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:116",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_access2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920528,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584040448,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:116",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smk_ipv4_check",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_access2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584040448,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584068976,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:116",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smk_ipv4_check",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_access2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068976,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584440800,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:115",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smk_ipv4_check",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_access2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440800,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585072512,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:115",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_post_notification",
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smk_ipv4_check",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_access2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072512,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585794416,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:115",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_post_notification",
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smk_ipv4_check",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_access2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585794416,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586026160,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:115",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_post_notification",
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smk_ipv4_check",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_access2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586026160,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586274576,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:115",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_post_notification",
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smk_ipv4_check",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_access2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586274576,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495344344,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:116",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495344344,
      "name": "smk_access",
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228720384,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:116",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228720384,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289350480,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:116",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289350480,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274555108,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:116",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274555108,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583537168,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:116",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537168,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583474224,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:116",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583474224,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583520944,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:116",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583520944,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int smk_access(struct smack_known * subject, struct smack_known * object, int request, struct smk_audit_info * a)
```

```json
{
  "name": "smk_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583617712,
      "name": "smk_access",
      "external": true,
      "loc": "security/smack/smack_access.c:116",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_netlabel_send",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583617712,
      "name": "smk_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
