# Function: <code>__sys_sendmmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586182384,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:1999",
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
      "addr": 18446744071586182384,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586602816,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:1994",
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
      "addr": 18446744071586602816,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586787264,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2037",
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
      "addr": 18446744071586787264,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586911264,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2087",
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
      "addr": 18446744071586911264,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587403200,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2080",
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
      "addr": 18446744071587403200,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587706720,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2182",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmmsg",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587706720,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587840176,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2169",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmmsg",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587840176,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588144160,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2372",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmmsg",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588144160,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588349216,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2413",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmmsg",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588349216,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589210304,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2455",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmmsg",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589210304,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589209408,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2448",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmmsg",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589209408,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589103024,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2438",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmmsg",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589103024,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589820672,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2511",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x64_compat_sys_sendmmsg",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589820672,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591341360,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2587",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591341360,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593096752,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2575",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593096752,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593548960,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2613",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593548960,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594321248,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2683",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594321248,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501855632,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2413",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__arm64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__arm64_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501855632,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1020
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234623864,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2413",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234623864,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295258032,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2413",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_socketcall",
        "net/socket.c:__se_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__se_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295258032,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278183654,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2413",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278183654,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587956000,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2413",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmmsg",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587956000,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587669104,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2413",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmmsg",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587669104,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588287776,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2413",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmmsg",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588287776,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
int __sys_sendmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, bool forbid_cmsg_compat)
```

```json
{
  "name": "__sys_sendmmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588422928,
      "name": "__sys_sendmmsg",
      "external": true,
      "loc": "net/socket.c:2413",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_sendmmsg",
        "net/socket.c:__x64_sys_sendmmsg",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_sendmmsg",
        "net/compat.c:__ia32_compat_sys_sendmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588422928,
      "name": "__sys_sendmmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
