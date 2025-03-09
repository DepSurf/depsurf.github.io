# Function: <code>__sys_sendmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586182208,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:1971",
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
      "addr": 18446744071586182208,
      "name": "__sys_sendmsg",
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586602640,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:1966",
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
      "addr": 18446744071586602640,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586787088,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2009",
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
      "addr": 18446744071586787088,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586911088,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2059",
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
      "addr": 18446744071586911088,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587403024,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2052",
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
      "addr": 18446744071587403024,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587706480,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2152",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmsg",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587706480,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587839936,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2139",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmsg",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587839936,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588143920,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2342",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmsg",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588143920,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588348976,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2383",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmsg",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588348976,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589210048,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2425",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmsg",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589210048,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589209152,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2418",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmsg",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589209152,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589102784,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2408",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmsg",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589102784,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589820432,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2481",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x64_compat_sys_sendmsg",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589820432,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591341024,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2557",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591341024,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593096368,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2545",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593096368,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593548576,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2583",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593548576,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594320864,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2653",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594320864,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501855368,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2383",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__arm64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__arm64_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501855368,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234623664,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2383",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234623664,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295257744,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2383",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_socketcall",
        "net/socket.c:__se_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__se_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295257744,
      "name": "__sys_sendmsg",
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278183466,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2383",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278183466,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587955760,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2383",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmsg",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587955760,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587668864,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2383",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmsg",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587668864,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588287536,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2383",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmsg",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588287536,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long int __sys_sendmsg(int fd, struct user_msghdr * msg, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588422688,
      "name": "__sys_sendmsg",
      "external": true,
      "loc": "net/socket.c:2383",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmsg",
        "net/socket.c:__x64_sys_sendmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmsg",
        "net/compat.c:__ia32_compat_sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588422688,
      "name": "__sys_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
