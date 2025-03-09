# Function: <code>__sys_sendto</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587705008,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1769",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705008,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587838464,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1756",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587838464,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588142368,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1921",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588142368,
      "name": "__sys_sendto",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588347264,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1921",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588347264,
      "name": "__sys_sendto",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589205792,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1964",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589205792,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589203824,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1944",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589203824,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589097408,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1935",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589097408,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589815056,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:2008",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589815056,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591335024,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:2088",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591335024,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593090176,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:2085",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593090176,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593542352,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:2117",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593542352,
      "name": "__sys_sendto",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594315008,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:2159",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594315008,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501853944,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1921",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__arm64_sys_send",
        "net/socket.c:__arm64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501853944,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234621504,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1921",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_send",
        "net/socket.c:__se_sys_sendto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234621504,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295256048,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1921",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_socketcall",
        "net/socket.c:__se_sys_socketcall",
        "net/socket.c:__se_sys_send",
        "net/socket.c:__se_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295256048,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278181686,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1921",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_send",
        "net/socket.c:__se_sys_sendto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278181686,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587954048,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1921",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587954048,
      "name": "__sys_sendto",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587667152,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1921",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587667152,
      "name": "__sys_sendto",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588285824,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1921",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588285824,
      "name": "__sys_sendto",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```

```json
{
  "name": "__sys_sendto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588420976,
      "name": "__sys_sendto",
      "external": true,
      "loc": "net/socket.c:1921",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_send",
        "net/socket.c:__x64_sys_send",
        "net/socket.c:__ia32_sys_sendto",
        "net/socket.c:__x64_sys_sendto",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588420976,
      "name": "__sys_sendto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int __sys_sendto(int fd, void * buff, size_t len, unsigned int flags, struct sockaddr * addr, int addr_len)
```
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
