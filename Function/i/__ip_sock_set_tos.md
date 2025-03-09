# Function: <code>__ip_sock_set_tos</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __ip_sock_set_tos(struct sock * sk, int val)
```

```json
{
  "name": "__ip_sock_set_tos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589984256,
      "name": "__ip_sock_set_tos",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:563",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589984256,
      "name": "__ip_sock_set_tos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void __ip_sock_set_tos(struct sock * sk, int val)
```

```json
{
  "name": "__ip_sock_set_tos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590025040,
      "name": "__ip_sock_set_tos",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:579",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590025040,
      "name": "__ip_sock_set_tos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void __ip_sock_set_tos(struct sock * sk, int val)
```

```json
{
  "name": "__ip_sock_set_tos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589939488,
      "name": "__ip_sock_set_tos",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:579",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589939488,
      "name": "__ip_sock_set_tos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void __ip_sock_set_tos(struct sock * sk, int val)
```

```json
{
  "name": "__ip_sock_set_tos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590706592,
      "name": "__ip_sock_set_tos",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:579",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590706592,
      "name": "__ip_sock_set_tos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void __ip_sock_set_tos(struct sock * sk, int val)
```

```json
{
  "name": "__ip_sock_set_tos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592345008,
      "name": "__ip_sock_set_tos",
      "external": true,
      "loc": "net/ipv4/ip_sockglue.c:581",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592345008,
      "name": "__ip_sock_set_tos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void __ip_sock_set_tos(struct sock * sk, int val)
```

```json
{
  "name": "__ip_sock_set_tos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594180976,
      "name": "__ip_sock_set_tos",
      "external": true,
      "loc": "net/ipv4/ip_sockglue.c:582",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594180976,
      "name": "__ip_sock_set_tos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void __ip_sock_set_tos(struct sock * sk, int val)
```

```json
{
  "name": "__ip_sock_set_tos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594568128,
      "name": "__ip_sock_set_tos",
      "external": true,
      "loc": "net/ipv4/ip_sockglue.c:589",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:ip_sock_set_tos",
        "net/mptcp/sockopt.c:sync_socket_options",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594568128,
      "name": "__ip_sock_set_tos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void __ip_sock_set_tos(struct sock * sk, int val)
```

```json
{
  "name": "__ip_sock_set_tos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595371504,
      "name": "__ip_sock_set_tos",
      "external": true,
      "loc": "net/ipv4/ip_sockglue.c:586",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595371504,
      "name": "__ip_sock_set_tos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __ip_sock_set_tos(struct sock * sk, int val)
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
