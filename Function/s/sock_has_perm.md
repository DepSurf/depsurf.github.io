# Function: <code>sock_has_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sock_has_perm(struct task_struct * task, struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582261184,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4051",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_getpeername",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_connect",
        "security/selinux/hooks.c:selinux_socket_bind",
        "security/selinux/hooks.c:selinux_netlink_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261184,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int sock_has_perm(struct task_struct * task, struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582479264,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4182",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getpeername",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_connect",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582479264,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int sock_has_perm(struct task_struct * task, struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571952,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4257",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getpeername",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_connect",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571952,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661408,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4231",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_connect",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661408,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817024,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4246",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_connect",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817024,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011200,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4514",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011200,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583124688,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4234",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583124688,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583311360,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4422",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getpeername",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311360,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583416512,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4480",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getpeername",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416512,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583784140,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4473",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757904,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583906396,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4489",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879408,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583931548,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4653",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905520,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584296540,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4638",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584269232,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584929852,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4542",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584883904,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585640908,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4560",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585590432,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585870940,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4521",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585821376,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4609",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586081152,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071597523317,
      "name": "sock_has_perm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495172576,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4480",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495172576,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228559648,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4480",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_connect_helper",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228559648,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289110608,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4480",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getpeername",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_connect_helper",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289110608,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274415000,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4480",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_connect_helper",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274415000,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583385248,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4480",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getpeername",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583385248,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583322336,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4480",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getpeername",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322336,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583369024,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4480",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getpeername",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369024,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int sock_has_perm(struct sock * sk, u32 perms)
```

```json
{
  "name": "sock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583464608,
      "name": "sock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:4480",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_netlink_send",
        "security/selinux/hooks.c:selinux_socket_shutdown",
        "security/selinux/hooks.c:selinux_socket_getsockopt",
        "security/selinux/hooks.c:selinux_socket_setsockopt",
        "security/selinux/hooks.c:selinux_socket_getpeername",
        "security/selinux/hooks.c:selinux_socket_getsockname",
        "security/selinux/hooks.c:selinux_socket_recvmsg",
        "security/selinux/hooks.c:selinux_socket_sendmsg",
        "security/selinux/hooks.c:selinux_socket_listen",
        "security/selinux/hooks.c:selinux_socket_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583464608,
      "name": "sock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * task</code>
</li>
<li>
<b>Param reordered. </b>
<code>task, sk, perms</code> ➡️ <code>sk, perms</code>
</li>
</ul>
</details>
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
