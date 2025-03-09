# Function: <code>__tcp_sock_set_nodelay</code>

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
  "name": "__tcp_sock_set_nodelay",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590022678,
      "name": "__tcp_sock_set_nodelay",
      "external": false,
      "loc": "net/ipv4/tcp.c:2900",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay"
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
  "name": "__tcp_sock_set_nodelay",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590064822,
      "name": "__tcp_sock_set_nodelay",
      "external": false,
      "loc": "net/ipv4/tcp.c:3158",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay"
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
  "name": "__tcp_sock_set_nodelay",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589979414,
      "name": "__tcp_sock_set_nodelay",
      "external": false,
      "loc": "net/ipv4/tcp.c:3212",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay"
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
  "name": "__tcp_sock_set_nodelay",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590748358,
      "name": "__tcp_sock_set_nodelay",
      "external": false,
      "loc": "net/ipv4/tcp.c:3236",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __tcp_sock_set_nodelay(struct sock * sk, bool on)
```

```json
{
  "name": "__tcp_sock_set_nodelay",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592380326,
      "name": "__tcp_sock_set_nodelay",
      "external": true,
      "loc": "net/ipv4/tcp.c:3254",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay"
      ],
      "caller_func": [
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592407392,
      "name": "__tcp_sock_set_nodelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void __tcp_sock_set_nodelay(struct sock * sk, bool on)
```

```json
{
  "name": "__tcp_sock_set_nodelay",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594257476,
      "name": "__tcp_sock_set_nodelay",
      "external": true,
      "loc": "net/ipv4/tcp.c:3353",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay"
      ],
      "caller_func": [
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594255408,
      "name": "__tcp_sock_set_nodelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void __tcp_sock_set_nodelay(struct sock * sk, bool on)
```

```json
{
  "name": "__tcp_sock_set_nodelay",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594643340,
      "name": "__tcp_sock_set_nodelay",
      "external": true,
      "loc": "net/ipv4/tcp.c:3245",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay"
      ],
      "caller_func": [
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594642208,
      "name": "__tcp_sock_set_nodelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void __tcp_sock_set_nodelay(struct sock * sk, bool on)
```

```json
{
  "name": "__tcp_sock_set_nodelay",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595448723,
      "name": "__tcp_sock_set_nodelay",
      "external": true,
      "loc": "net/ipv4/tcp.c:3251",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595419360,
      "name": "__tcp_sock_set_nodelay.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071595445504,
      "name": "__tcp_sock_set_nodelay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void __tcp_sock_set_nodelay(struct sock * sk, bool on)
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
