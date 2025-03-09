# Function: <code>sock_alloc_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586166880,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:355",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_map_fd",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166880,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586587328,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:355",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:sock_map_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586587328,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586771696,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:397",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:sock_map_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586771696,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586896800,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:395",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:sock_map_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586896800,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587388912,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:395",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:sock_map_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388912,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587689824,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:389",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587689824,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587821840,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:387",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587821840,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588125040,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:390",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588125040,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588329808,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:390",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588329808,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589190432,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:404",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589190432,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589188880,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:404",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589188880,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589082976,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:405",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589082976,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589801968,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:455",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589801968,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591319904,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:456",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sys_socket_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591319904,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593073680,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:458",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sys_socket_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593073680,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593524976,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:460",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sys_socket_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593524976,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594296208,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:462",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_accept",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sys_socket_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594296208,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501825336,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:390",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501825336,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234607828,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:390",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234607828,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295226032,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:390",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295226032,
      "name": "sock_alloc_file",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278170724,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:390",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278170724,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587936592,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:390",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587936592,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587649696,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:390",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587649696,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588268368,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:390",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588268368,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
struct file * sock_alloc_file(struct socket * sock, int flags, const char * dname)
```

```json
{
  "name": "sock_alloc_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588403648,
      "name": "sock_alloc_file",
      "external": true,
      "loc": "net/socket.c:390",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588403648,
      "name": "sock_alloc_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
