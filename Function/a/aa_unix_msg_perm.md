# Function: <code>aa_unix_msg_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582593584,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:438",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_msg_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593584,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582837136,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:438",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_msg_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582837136,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582933008,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:438",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_msg_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582933008,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582987840,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:445",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_msg_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582987840,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583152096,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:445",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_sock_msg_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583152096,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583356624,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583356624,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583475312,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583475312,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583659664,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583659664,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583765952,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583765952,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584157600,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157600,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584275952,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584275952,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584301344,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584301344,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584687776,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687776,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585350800,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:467",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350800,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586091936,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:485",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586091936,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586327408,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:485",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586327408,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586584144,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:485",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586584144,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495566496,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495566496,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228929908,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228929908,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289659680,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289659680,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274736110,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274736110,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583734688,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734688,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583671744,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583671744,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583718464,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718464,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int aa_unix_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_unix_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583818976,
      "name": "aa_unix_msg_perm",
      "external": true,
      "loc": "security/apparmor/af_unix.c:446",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583818976,
      "name": "aa_unix_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
