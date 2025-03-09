# Function: <code>sockfd_lookup_light</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586173936,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:449",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SYSC_getsockname",
        "net/socket.c:SYSC_getpeername",
        "net/socket.c:SYSC_recvfrom",
        "net/socket.c:SYSC_bind",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586173936,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586594592,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:449",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:SYSC_recvfrom",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:SYSC_getpeername",
        "net/socket.c:SYSC_getsockname",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SYSC_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586594592,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586778960,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:491",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:SYSC_recvfrom",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:SYSC_getpeername",
        "net/socket.c:SYSC_getsockname",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SYSC_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586778960,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586900080,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:489",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:SYSC_recvfrom",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:SYSC_getpeername",
        "net/socket.c:SYSC_getsockname",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SYSC_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586900080,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587391824,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:495",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:SYSC_recvfrom",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:SYSC_getpeername",
        "net/socket.c:SYSC_getsockname",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SYSC_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587391824,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587692480,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:489",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587692480,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587826576,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:468",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587826576,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588129440,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:479",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588129440,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588334576,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:479",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588334576,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589194080,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:494",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589194080,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589192608,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:494",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589192608,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589086128,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:495",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589086128,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589803040,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:545",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589803040,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591321360,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:546",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591321360,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593075008,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:548",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593075008,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593526512,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:551",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593526512,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594297936,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:553",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594297936,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501828336,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:479",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__arm64_sys_getsockopt",
        "net/socket.c:__arm64_sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501828336,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234609988,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:479",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__se_sys_getsockopt",
        "net/socket.c:__se_sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234609988,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295230544,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:479",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295230544,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278174702,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:479",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__se_sys_getsockopt",
        "net/socket.c:__se_sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278174702,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587941360,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:479",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587941360,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587654464,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:479",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587654464,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588273136,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:479",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588273136,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
struct socket * sockfd_lookup_light(int fd, int * err, int * fput_needed)
```

```json
{
  "name": "sockfd_lookup_light",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588408448,
      "name": "sockfd_lookup_light",
      "external": false,
      "loc": "net/socket.c:479",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_recvmmsg",
        "net/socket.c:__sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmsg",
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_getsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_getpeername",
        "net/socket.c:__sys_getsockname",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_listen",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588408448,
      "name": "sockfd_lookup_light",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
