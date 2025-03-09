# Function: <code>aa_sk_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583232,
      "name": "aa_sk_perm",
      "external": false,
      "loc": "security/apparmor/net.c:209",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_perm",
        "security/apparmor/net.c:aa_sock_bind_perm",
        "security/apparmor/net.c:aa_sock_connect_perm",
        "security/apparmor/net.c:aa_sock_listen_perm",
        "security/apparmor/net.c:aa_sock_accept_perm",
        "security/apparmor/net.c:aa_sock_msg_perm",
        "security/apparmor/net.c:aa_sock_opt_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583232,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582826320,
      "name": "aa_sk_perm",
      "external": false,
      "loc": "security/apparmor/net.c:209",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_opt_perm",
        "security/apparmor/net.c:aa_sock_msg_perm",
        "security/apparmor/net.c:aa_sock_accept_perm",
        "security/apparmor/net.c:aa_sock_listen_perm",
        "security/apparmor/net.c:aa_sock_connect_perm",
        "security/apparmor/net.c:aa_sock_bind_perm",
        "security/apparmor/net.c:aa_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582826320,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922192,
      "name": "aa_sk_perm",
      "external": false,
      "loc": "security/apparmor/net.c:209",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_opt_perm",
        "security/apparmor/net.c:aa_sock_msg_perm",
        "security/apparmor/net.c:aa_sock_accept_perm",
        "security/apparmor/net.c:aa_sock_listen_perm",
        "security/apparmor/net.c:aa_sock_connect_perm",
        "security/apparmor/net.c:aa_sock_bind_perm",
        "security/apparmor/net.c:aa_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922192,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980880,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:208",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_opt_perm",
        "security/apparmor/net.c:aa_sock_msg_perm",
        "security/apparmor/net.c:aa_sock_accept_perm",
        "security/apparmor/net.c:aa_sock_listen_perm",
        "security/apparmor/net.c:aa_sock_connect_perm",
        "security/apparmor/net.c:aa_sock_bind_perm",
        "security/apparmor/net.c:aa_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980880,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583144752,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:208",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_opt_perm",
        "security/apparmor/net.c:aa_sock_msg_perm",
        "security/apparmor/net.c:aa_sock_accept_perm",
        "security/apparmor/net.c:aa_sock_listen_perm",
        "security/apparmor/net.c:aa_sock_connect_perm",
        "security/apparmor/net.c:aa_sock_bind_perm",
        "security/apparmor/net.c:aa_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583144752,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583350672,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:228",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:aa_sock_perm",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583350672,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583469328,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:231",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:aa_sock_perm",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583469328,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583653728,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:227",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:aa_sock_perm",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583653728,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583760016,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:227",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:aa_sock_perm",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583760016,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584150272,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:228",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_shutdown",
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getpeername",
        "security/apparmor/lsm.c:apparmor_socket_getsockname",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584150272,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584268608,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:230",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_shutdown",
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getpeername",
        "security/apparmor/lsm.c:apparmor_socket_getsockname",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268608,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584293856,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:230",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_shutdown",
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getpeername",
        "security/apparmor/lsm.c:apparmor_socket_getsockname",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293856,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584680288,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:230",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_shutdown",
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getpeername",
        "security/apparmor/lsm.c:apparmor_socket_getsockname",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584680288,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585340000,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:231",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_shutdown",
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getpeername",
        "security/apparmor/lsm.c:apparmor_socket_getsockname",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340000,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586080704,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:236",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_shutdown",
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getpeername",
        "security/apparmor/lsm.c:apparmor_socket_getsockname",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586080704,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586316016,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:236",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_shutdown",
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getpeername",
        "security/apparmor/lsm.c:apparmor_socket_getsockname",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586316016,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586572576,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:239",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_shutdown",
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getpeername",
        "security/apparmor/lsm.c:apparmor_socket_getsockname",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586572576,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495560160,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:227",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:aa_sock_perm",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495560160,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228923312,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:227",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:aa_sock_perm",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228923312,
      "name": "aa_sk_perm",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289651104,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:227",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:aa_sock_perm",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289651104,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274730488,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:227",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:aa_sock_perm",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274730488,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728752,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:227",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:aa_sock_perm",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728752,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583665808,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:227",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:aa_sock_perm",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583665808,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583712528,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:227",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:aa_sock_perm",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712528,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int aa_sk_perm(const char * op, u32 request, struct sock * sk)
```

```json
{
  "name": "aa_sk_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583813024,
      "name": "aa_sk_perm",
      "external": true,
      "loc": "security/apparmor/net.c:227",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_setsockopt",
        "security/apparmor/lsm.c:apparmor_socket_getsockopt",
        "security/apparmor/lsm.c:aa_sock_perm",
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg",
        "security/apparmor/lsm.c:apparmor_socket_accept",
        "security/apparmor/lsm.c:apparmor_socket_listen",
        "security/apparmor/lsm.c:apparmor_socket_connect",
        "security/apparmor/lsm.c:apparmor_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583813024,
      "name": "aa_sk_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
