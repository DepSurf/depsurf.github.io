# Function: <code>mptcp_get_sub_addrs</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_get_sub_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593736522,
      "name": "mptcp_get_sub_addrs",
      "external": false,
      "loc": "net/mptcp/sockopt.c:1030",
      "file": "net/mptcp/sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs"
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
  "name": "mptcp_get_sub_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595670122,
      "name": "mptcp_get_sub_addrs",
      "external": false,
      "loc": "net/mptcp/sockopt.c:1047",
      "file": "net/mptcp/sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_get_sub_addrs(const struct sock * sk, struct mptcp_subflow_addrs * a)
```

```json
{
  "name": "mptcp_get_sub_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_get_sub_addrs",
      "external": false,
      "loc": "net/mptcp/sockopt.c:1075",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sockopt.c:mptcp_getsockopt_full_info",
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596178800,
      "name": "mptcp_get_sub_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071596900869,
      "name": "mptcp_get_sub_addrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void mptcp_get_sub_addrs(const struct sock * sk, struct mptcp_subflow_addrs * a)
```

```json
{
  "name": "mptcp_get_sub_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_get_sub_addrs",
      "external": false,
      "loc": "net/mptcp/sockopt.c:1091",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sockopt.c:mptcp_getsockopt_full_info",
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597053888,
      "name": "mptcp_get_sub_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071597826085,
      "name": "mptcp_get_sub_addrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void mptcp_get_sub_addrs(const struct sock * sk, struct mptcp_subflow_addrs * a)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
