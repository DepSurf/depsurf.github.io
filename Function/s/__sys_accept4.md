# Function: <code>__sys_accept4</code>

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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587703408,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1553",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703408,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587836864,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1540",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587836864,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588140752,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1705",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588140752,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588345648,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1705",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588345648,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589204528,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1797",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589204528,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589202560,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1777",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589202560,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589096144,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1768",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589096144,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589813792,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1841",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589813792,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591333456,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1921",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591333456,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593088336,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1919",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593088336,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593540480,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1949",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593540480,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594313136,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1991",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594313136,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501852456,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1705",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__arm64_sys_accept",
        "net/socket.c:__arm64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501852456,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234620208,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1705",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_accept",
        "net/socket.c:__se_sys_accept4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234620208,
      "name": "__sys_accept4",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295254096,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1705",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_socketcall",
        "net/socket.c:__se_sys_socketcall",
        "net/socket.c:__se_sys_accept",
        "net/socket.c:__se_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295254096,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278180468,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1705",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_accept",
        "net/socket.c:__se_sys_accept4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278180468,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587952432,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1705",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587952432,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587665536,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1705",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587665536,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588284208,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1705",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588284208,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "__sys_accept4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588419360,
      "name": "__sys_accept4",
      "external": true,
      "loc": "net/socket.c:1705",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_accept",
        "net/socket.c:__x64_sys_accept",
        "net/socket.c:__ia32_sys_accept4",
        "net/socket.c:__x64_sys_accept4",
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588419360,
      "name": "__sys_accept4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
int __sys_accept4(int fd, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
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
