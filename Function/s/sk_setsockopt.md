# Function: <code>sk_setsockopt</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int sk_setsockopt(struct sock * sk, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "sk_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593126320,
      "name": "sk_setsockopt",
      "external": true,
      "loc": "net/core/sock.c:1087",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/filter.c:sol_socket_sockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593126320,
      "name": "sk_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5115
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
int sk_setsockopt(struct sock * sk, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "sk_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593578928,
      "name": "sk_setsockopt",
      "external": true,
      "loc": "net/core/sock.c:1094",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/filter.c:sol_socket_sockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593578928,
      "name": "sk_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5054
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
int sk_setsockopt(struct sock * sk, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "sk_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594351440,
      "name": "sk_setsockopt",
      "external": true,
      "loc": "net/core/sock.c:1090",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/filter.c:sol_socket_sockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594351440,
      "name": "sk_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5286
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int sk_setsockopt(struct sock * sk, int level, int optname, sockptr_t optval, unsigned int optlen)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
