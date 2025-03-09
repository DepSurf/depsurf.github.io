# Function: <code>__sys_connect</code>

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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587704080,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1658",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587704080,
      "name": "__sys_connect",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587837536,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1645",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837536,
      "name": "__sys_connect",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588141424,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1810",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588141424,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588346320,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1810",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588346320,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589204944,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1860",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589204944,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589202976,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1841",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589202976,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589096544,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1832",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589096544,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589814192,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1905",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589814192,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591333968,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1985",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591333968,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593088976,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1982",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593088976,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593541136,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:2012",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593541136,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594313792,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:2054",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594313792,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501853072,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1810",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__arm64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501853072,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234620756,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1810",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234620756,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295254944,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1810",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_socketcall",
        "net/socket.c:__se_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295254944,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278180994,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1810",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278180994,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587953104,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1810",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587953104,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587666208,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1810",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587666208,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588284880,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1810",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588284880,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
```

```json
{
  "name": "__sys_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588420032,
      "name": "__sys_connect",
      "external": true,
      "loc": "net/socket.c:1810",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_connect",
        "net/socket.c:__x64_sys_connect",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588420032,
      "name": "__sys_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int __sys_connect(int fd, struct sockaddr * uservaddr, int addrlen)
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
