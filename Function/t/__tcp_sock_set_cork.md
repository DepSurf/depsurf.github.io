# Function: <code>__tcp_sock_set_cork</code>

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
  "name": "__tcp_sock_set_cork",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590019992,
      "name": "__tcp_sock_set_cork",
      "external": false,
      "loc": "net/ipv4/tcp.c:2872",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sock_set_cork"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_cork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590019840,
      "name": "__tcp_sock_set_cork.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tcp_sock_set_cork",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590062344,
      "name": "__tcp_sock_set_cork",
      "external": false,
      "loc": "net/ipv4/tcp.c:3130",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sock_set_cork"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_cork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590062192,
      "name": "__tcp_sock_set_cork.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tcp_sock_set_cork",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589977112,
      "name": "__tcp_sock_set_cork",
      "external": false,
      "loc": "net/ipv4/tcp.c:3184",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sock_set_cork"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_cork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589976960,
      "name": "__tcp_sock_set_cork.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tcp_sock_set_cork",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590745656,
      "name": "__tcp_sock_set_cork",
      "external": false,
      "loc": "net/ipv4/tcp.c:3208",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sock_set_cork"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_cork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590745504,
      "name": "__tcp_sock_set_cork.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __tcp_sock_set_cork(struct sock * sk, bool on)
```

```json
{
  "name": "__tcp_sock_set_cork",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592378537,
      "name": "__tcp_sock_set_cork",
      "external": true,
      "loc": "net/ipv4/tcp.c:3226",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sock_set_cork"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_cork",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592378368,
      "name": "__tcp_sock_set_cork.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071592407232,
      "name": "__tcp_sock_set_cork",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void __tcp_sock_set_cork(struct sock * sk, bool on)
```

```json
{
  "name": "__tcp_sock_set_cork",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594257159,
      "name": "__tcp_sock_set_cork",
      "external": true,
      "loc": "net/ipv4/tcp.c:3325",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_cork"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_cork",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594228032,
      "name": "__tcp_sock_set_cork.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071594255232,
      "name": "__tcp_sock_set_cork",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void __tcp_sock_set_cork(struct sock * sk, bool on)
```

```json
{
  "name": "__tcp_sock_set_cork",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594645065,
      "name": "__tcp_sock_set_cork",
      "external": true,
      "loc": "net/ipv4/tcp.c:3217",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_cork"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_cork",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594615056,
      "name": "__tcp_sock_set_cork.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071594642032,
      "name": "__tcp_sock_set_cork",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __tcp_sock_set_cork(struct sock * sk, bool on)
```

```json
{
  "name": "__tcp_sock_set_cork",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595448751,
      "name": "__tcp_sock_set_cork",
      "external": true,
      "loc": "net/ipv4/tcp.c:3223",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_cork"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_cork",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595418144,
      "name": "__tcp_sock_set_cork.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071595445328,
      "name": "__tcp_sock_set_cork",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __tcp_sock_set_cork(struct sock * sk, bool on)
```
</details>
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
