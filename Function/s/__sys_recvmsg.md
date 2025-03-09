# Function: <code>__sys_recvmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586182848,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2135",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586182848,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586603344,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2134",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586603344,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586787792,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2179",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586787792,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586911776,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2229",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586911776,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587403712,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2222",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587403712,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587707344,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2325",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvmsg",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587707344,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587840800,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2312",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvmsg",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587840800,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588144848,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2523",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvmsg",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588144848,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588350112,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2603",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvmsg",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588350112,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589211072,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2637",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvmsg",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211072,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589210176,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2632",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvmsg",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589210176,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589103728,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2616",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvmsg",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589103728,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589821376,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2689",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x64_compat_sys_recvmsg",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589821376,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591342224,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2765",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591342224,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593097696,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2753",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593097696,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593549904,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2791",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593549904,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594322192,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2861",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594322192,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501856976,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2603",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__arm64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__arm64_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501856976,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234624540,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2603",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234624540,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295259376,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2603",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_socketcall",
        "net/socket.c:__se_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__se_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295259376,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278184234,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2603",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278184234,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587956896,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2603",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvmsg",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587956896,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587670000,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2603",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvmsg",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587670000,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588288672,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2603",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvmsg",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588288672,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long int __sys_recvmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588423744,
      "name": "__sys_recvmsg",
      "external": true,
      "loc": "net/socket.c:2603",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recvmsg",
        "net/socket.c:__x64_sys_recvmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvmsg",
        "net/compat.c:__ia32_compat_sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588423744,
      "name": "__sys_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool forbid_cmsg_compat</code>
</li>
</ul>
</details>
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
