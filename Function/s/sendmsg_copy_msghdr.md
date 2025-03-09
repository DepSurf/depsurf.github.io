# Function: <code>sendmsg_copy_msghdr</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588348844,
      "name": "sendmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2316",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int sendmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct iovec * * iov)
```

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589209648,
      "name": "sendmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2371",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sendmsg",
        "fs/io_uring.c:io_sendmsg_prep",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589209648,
      "name": "sendmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int sendmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct iovec * * iov)
```

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589208752,
      "name": "sendmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2364",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_sendmsg",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589208752,
      "name": "sendmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int sendmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct iovec * * iov)
```

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589102400,
      "name": "sendmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2358",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sendmsg",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589102400,
      "name": "sendmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int sendmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct iovec * * iov)
```

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589820048,
      "name": "sendmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2431",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sendmsg",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589820048,
      "name": "sendmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int sendmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct iovec * * iov)
```

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591340560,
      "name": "sendmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2507",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_sendmsg",
        "net/socket.c:___sys_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591340560,
      "name": "sendmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sendmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct iovec * * iov)
```

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593096050,
      "name": "sendmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2495",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:___sys_sendmsg"
      ],
      "caller_func": [
        "io_uring/net.c:io_sendmsg_zc",
        "io_uring/net.c:io_sendmsg",
        "io_uring/net.c:io_sendmsg_prep_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593096208,
      "name": "sendmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sendmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct iovec * * iov)
```

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593548258,
      "name": "sendmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2533",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:___sys_sendmsg"
      ],
      "caller_func": [
        "io_uring/net.c:io_sendmsg_zc",
        "io_uring/net.c:io_sendmsg",
        "io_uring/net.c:io_sendmsg_prep_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593548416,
      "name": "sendmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sendmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct iovec * * iov)
```

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594320546,
      "name": "sendmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2603",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:___sys_sendmsg"
      ],
      "caller_func": [
        "io_uring/net.c:io_sendmsg_zc",
        "io_uring/net.c:io_sendmsg",
        "io_uring/net.c:io_sendmsg_prep_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594320704,
      "name": "sendmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501855196,
      "name": "sendmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2316",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234623548,
      "name": "sendmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2316",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295257552,
      "name": "sendmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2316",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278183322,
      "name": "sendmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2316",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587955628,
      "name": "sendmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2316",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587668732,
      "name": "sendmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2316",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588287404,
      "name": "sendmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2316",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sendmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588422556,
      "name": "sendmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2316",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_sendmsg_sock",
        "net/socket.c:___sys_sendmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int sendmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct iovec * * iov)
```
</details>
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
