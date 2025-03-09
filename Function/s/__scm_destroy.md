# Function: <code>__scm_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586244144,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:118",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_destruct_scm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586244144,
      "name": "__scm_destroy",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586667968,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:118",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586667968,
      "name": "__scm_destroy",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586852928,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:118",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586852928,
      "name": "__scm_destroy",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586976144,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:119",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586976144,
      "name": "__scm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587474352,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:119",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587474352,
      "name": "__scm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587779312,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:119",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587779312,
      "name": "__scm_destroy",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587912224,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:119",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587912224,
      "name": "__scm_destroy",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588220272,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588220272,
      "name": "__scm_destroy",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588424880,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588424880,
      "name": "__scm_destroy",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589291824,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589291824,
      "name": "__scm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589290784,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589290784,
      "name": "__scm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589184672,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589184672,
      "name": "__scm_destroy",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589906144,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589906144,
      "name": "__scm_destroy",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591436144,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591436144,
      "name": "__scm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593202528,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593202528,
      "name": "__scm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593662576,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593662576,
      "name": "__scm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594440592,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:122",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594440592,
      "name": "__scm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501942696,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501942696,
      "name": "__scm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234699892,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234699892,
      "name": "__scm_destroy",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295364368,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295364368,
      "name": "__scm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278248776,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278248776,
      "name": "__scm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588031664,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588031664,
      "name": "__scm_destroy",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587744752,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587744752,
      "name": "__scm_destroy",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588363440,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588363440,
      "name": "__scm_destroy",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __scm_destroy(struct scm_cookie * scm)
```

```json
{
  "name": "__scm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588499008,
      "name": "__scm_destroy",
      "external": true,
      "loc": "net/core/scm.c:116",
      "file": "net/core/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:__scm_send",
        "net/compat.c:scm_detach_fds_compat",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/scm.c:unix_destruct_scm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588499008,
      "name": "__scm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
