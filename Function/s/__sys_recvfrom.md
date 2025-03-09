# Function: <code>__sys_recvfrom</code>

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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587705616,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:1830",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__x32_compat_sys_recv",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705616,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587839072,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:1817",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__x32_compat_sys_recv",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587839072,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588142960,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:1982",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__x32_compat_sys_recv",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588142960,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588347856,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:1982",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__x32_compat_sys_recv",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588347856,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589206384,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:2025",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__x32_compat_sys_recv",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589206384,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589204416,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:2005",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__x32_compat_sys_recv",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589204416,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589098000,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:1996",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__x32_compat_sys_recv",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589098000,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589815648,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:2069",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x64_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__x64_compat_sys_recv",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589815648,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591335696,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:2149",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591335696,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593090944,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:2147",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593090944,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593543120,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:2180",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593543120,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594315904,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:2221",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594315904,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501854408,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:1982",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__arm64_sys_recv",
        "net/socket.c:__arm64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__arm64_compat_sys_recvfrom",
        "net/compat.c:__arm64_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501854408,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234621892,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:1982",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_recv",
        "net/socket.c:__se_sys_recvfrom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234621892,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295256608,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:1982",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_socketcall",
        "net/socket.c:__se_sys_socketcall",
        "net/socket.c:__se_sys_recv",
        "net/socket.c:__se_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__se_compat_sys_recvfrom",
        "net/compat.c:__se_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295256608,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278182118,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:1982",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_recv",
        "net/socket.c:__se_sys_recvfrom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278182118,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587954640,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:1982",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__x32_compat_sys_recv",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587954640,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587667744,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:1982",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__x32_compat_sys_recv",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587667744,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588286416,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:1982",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__x32_compat_sys_recv",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588286416,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
```

```json
{
  "name": "__sys_recvfrom",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588421568,
      "name": "__sys_recvfrom",
      "external": true,
      "loc": "net/socket.c:1982",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_recv",
        "net/socket.c:__x64_sys_recv",
        "net/socket.c:__ia32_sys_recvfrom",
        "net/socket.c:__x64_sys_recvfrom",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_recvfrom",
        "net/compat.c:__ia32_compat_sys_recvfrom",
        "net/compat.c:__x32_compat_sys_recv",
        "net/compat.c:__ia32_compat_sys_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588421568,
      "name": "__sys_recvfrom",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int __sys_recvfrom(int fd, void * ubuf, size_t size, unsigned int flags, struct sockaddr * addr, int * addr_len)
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
