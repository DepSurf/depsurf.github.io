# Function: <code>move_addr_to_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586177792,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:188",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:SYSC_bind",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:copy_msghdr_from_user"
      ],
      "caller_func": [
        "net/socket.c:SYSC_bind",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:copy_msghdr_from_user",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586177792,
      "name": "move_addr_to_kernel.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071586180416,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586599555,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:188",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586598128,
      "name": "move_addr_to_kernel.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071586600848,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586784003,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:188",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586782576,
      "name": "move_addr_to_kernel.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071586785296,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586907909,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:188",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586906608,
      "name": "move_addr_to_kernel.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071586909328,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587399829,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:188",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:SYSC_sendto",
        "net/socket.c:SYSC_connect",
        "net/socket.c:SYSC_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587398512,
      "name": "move_addr_to_kernel.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071587401248,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587697386,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:182",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587697008,
      "name": "move_addr_to_kernel.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071587701808,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587833173,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:182",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587832800,
      "name": "move_addr_to_kernel.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071587835264,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588136965,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:178",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588136576,
      "name": "move_addr_to_kernel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071588139120,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588338021,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:178",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588337632,
      "name": "move_addr_to_kernel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071588344016,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589207540,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:192",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "fs/io_uring.c:io_connect",
        "fs/io_uring.c:io_connect_prep",
        "net/socket.c:__copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:__get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589199680,
      "name": "move_addr_to_kernel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071589202384,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589206676,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:192",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_connect",
        "net/socket.c:__copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:__get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589197568,
      "name": "move_addr_to_kernel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071589200416,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589100323,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:192",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "fs/io_uring.c:io_connect",
        "net/socket.c:__copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:__get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589093776,
      "name": "move_addr_to_kernel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071589094016,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589817971,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:242",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "fs/io_uring.c:io_connect",
        "net/socket.c:__copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:__get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589806560,
      "name": "move_addr_to_kernel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071589809744,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591328656,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:243",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_connect",
        "net/socket.c:__copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:__get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591328656,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593083456,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:243",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_connect",
        "io_uring/net.c:io_connect_prep_async",
        "io_uring/net.c:io_send_zc",
        "io_uring/net.c:io_send",
        "io_uring/net.c:io_send_prep_async",
        "net/socket.c:__copy_msghdr",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:__get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593083456,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593535632,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:245",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_connect",
        "io_uring/net.c:io_connect_prep_async",
        "io_uring/net.c:io_send_zc",
        "io_uring/net.c:io_send",
        "io_uring/net.c:io_send_prep_async",
        "net/socket.c:__copy_msghdr",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:__get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593535632,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594308240,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:247",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_connect",
        "io_uring/net.c:io_connect_prep_async",
        "io_uring/net.c:io_send_zc",
        "io_uring/net.c:io_send",
        "io_uring/net.c:io_send_prep_async",
        "net/socket.c:__copy_msghdr",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:__get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594308240,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501837504,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:178",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501836488,
      "name": "move_addr_to_kernel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446603336501850568,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234616888,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:178",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234616888,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295237156,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:178",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295236608,
      "name": "move_addr_to_kernel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 13835058055295251712,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278177850,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:178",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278177556,
      "name": "move_addr_to_kernel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446743936278179076,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587944805,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:178",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587944416,
      "name": "move_addr_to_kernel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071587950800,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587657909,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:178",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587657520,
      "name": "move_addr_to_kernel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071587663904,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588276581,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:178",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588276192,
      "name": "move_addr_to_kernel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071588282576,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int move_addr_to_kernel(void * uaddr, int ulen, struct __kernel_sockaddr_storage * kaddr)
```

```json
{
  "name": "move_addr_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588411877,
      "name": "move_addr_to_kernel",
      "external": true,
      "loc": "net/socket.c:178",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind"
      ],
      "caller_func": [
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__sys_sendto",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_bind",
        "net/compat.c:get_compat_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588411488,
      "name": "move_addr_to_kernel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071588417728,
      "name": "move_addr_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
