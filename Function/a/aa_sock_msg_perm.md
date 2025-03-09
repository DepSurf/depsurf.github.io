# Function: <code>aa_sock_msg_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_sock_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585488,
      "name": "aa_sock_msg_perm",
      "external": true,
      "loc": "security/apparmor/net.c:320",
      "file": "security/apparmor/net.c",
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
      "addr": 18446744071582585488,
      "name": "aa_sock_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int aa_sock_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582828672,
      "name": "aa_sock_msg_perm",
      "external": true,
      "loc": "security/apparmor/net.c:320",
      "file": "security/apparmor/net.c",
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
      "addr": 18446744071582828672,
      "name": "aa_sock_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int aa_sock_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582924544,
      "name": "aa_sock_msg_perm",
      "external": true,
      "loc": "security/apparmor/net.c:320",
      "file": "security/apparmor/net.c",
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
      "addr": 18446744071582924544,
      "name": "aa_sock_msg_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int aa_sock_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981536,
      "name": "aa_sock_msg_perm",
      "external": true,
      "loc": "security/apparmor/net.c:319",
      "file": "security/apparmor/net.c",
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
      "addr": 18446744071582981536,
      "name": "aa_sock_msg_perm",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int aa_sock_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583145504,
      "name": "aa_sock_msg_perm",
      "external": true,
      "loc": "security/apparmor/net.c:319",
      "file": "security/apparmor/net.c",
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
      "addr": 18446744071583145504,
      "name": "aa_sock_msg_perm",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583304149,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:1018",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583422933,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:987",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583608821,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:983",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583714997,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:983",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584087573,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:1048",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584206853,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:1048",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584233493,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:1057",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584618997,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:1057",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585271349,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:1276",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586006677,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:1333",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586240037,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:1483",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586493065,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:1515",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495509260,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:983",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228876760,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:983",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289579852,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:983",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274691092,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:983",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583683733,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:983",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583620789,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:983",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583667509,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:983",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
  "name": "aa_sock_msg_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583766197,
      "name": "aa_sock_msg_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:983",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_recvmsg",
        "security/apparmor/lsm.c:apparmor_socket_sendmsg"
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
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int aa_sock_msg_perm(const char * op, u32 request, struct socket * sock, struct msghdr * msg, int size)
```
</details>
</li>
</ul>
