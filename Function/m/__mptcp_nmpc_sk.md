# Function: <code>__mptcp_nmpc_sk</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct sock * __mptcp_nmpc_sk(struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_nmpc_sk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596960835,
      "name": "__mptcp_nmpc_sk",
      "external": true,
      "loc": "net/mptcp/protocol.c:98",
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
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_ip_set",
        "net/mptcp/sockopt.c:mptcp_setsockopt_v6",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597823682,
      "name": "__mptcp_nmpc_sk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071596960768,
      "name": "__mptcp_nmpc_sk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct sock * __mptcp_nmpc_sk(struct mptcp_sock * msk)
```
</details>
</li>
</ul>
