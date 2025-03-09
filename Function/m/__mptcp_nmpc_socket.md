# Function: <code>__mptcp_nmpc_socket</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mptcp_nmpc_socket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591079027,
      "name": "__mptcp_nmpc_socket",
      "external": false,
      "loc": "net/mptcp/protocol.c:47",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_poll",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_get_port",
        "net/mptcp/protocol.c:mptcp_accept",
        "net/mptcp/protocol.c:__mptcp_socket_create"
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
  "name": "__mptcp_nmpc_socket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591158373,
      "name": "__mptcp_nmpc_socket",
      "external": false,
      "loc": "net/mptcp/protocol.c:54",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_get_port",
        "net/mptcp/protocol.c:mptcp_setsockopt",
        "net/mptcp/protocol.c:mptcp_setsockopt",
        "net/mptcp/protocol.c:mptcp_accept"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct socket * __mptcp_nmpc_socket(const struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_nmpc_socket",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591090677,
      "name": "__mptcp_nmpc_socket",
      "external": true,
      "loc": "net/mptcp/protocol.c:58",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_get_port",
        "net/mptcp/protocol.c:mptcp_accept"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591093392,
      "name": "__mptcp_nmpc_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct socket * __mptcp_nmpc_socket(const struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_nmpc_socket",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591928869,
      "name": "__mptcp_nmpc_socket",
      "external": true,
      "loc": "net/mptcp/protocol.c:63",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_get_port",
        "net/mptcp/protocol.c:mptcp_accept"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592752642,
      "name": "__mptcp_nmpc_socket.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591929808,
      "name": "__mptcp_nmpc_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct socket * __mptcp_nmpc_socket(const struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_nmpc_socket",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593651018,
      "name": "__mptcp_nmpc_socket",
      "external": true,
      "loc": "net/mptcp/protocol.c:65",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_get_port",
        "net/mptcp/protocol.c:mptcp_accept"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v4",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594639588,
      "name": "__mptcp_nmpc_socket.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593654304,
      "name": "__mptcp_nmpc_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct socket * __mptcp_nmpc_socket(const struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_nmpc_socket",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595578586,
      "name": "__mptcp_nmpc_socket",
      "external": true,
      "loc": "net/mptcp/protocol.c:56",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_get_port",
        "net/mptcp/protocol.c:mptcp_accept",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v4",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596368914,
      "name": "__mptcp_nmpc_socket.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595583440,
      "name": "__mptcp_nmpc_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct socket * __mptcp_nmpc_socket(struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_nmpc_socket",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596091779,
      "name": "__mptcp_nmpc_socket",
      "external": true,
      "loc": "net/mptcp/protocol.c:111",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket",
        "net/mptcp/sockopt.c:mptcp_getsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v4",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596898516,
      "name": "__mptcp_nmpc_socket.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071596091712,
      "name": "__mptcp_nmpc_socket",
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct socket * __mptcp_nmpc_socket(const struct mptcp_sock * msk)
```
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct mptcp_sock * msk</code> ➡️ <code>struct mptcp_sock * msk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct socket * __mptcp_nmpc_socket(struct mptcp_sock * msk)
```
</details>
</li>
</ul>
