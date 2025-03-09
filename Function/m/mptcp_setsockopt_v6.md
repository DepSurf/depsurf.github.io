# Function: <code>mptcp_setsockopt_v6</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_setsockopt_v6",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591143860,
      "name": "mptcp_setsockopt_v6",
      "external": false,
      "loc": "net/mptcp/protocol.c:2839",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_setsockopt"
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
  "name": "mptcp_setsockopt_v6",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591151876,
      "name": "mptcp_setsockopt_v6",
      "external": false,
      "loc": "net/mptcp/sockopt.c:273",
      "file": "net/mptcp/sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_setsockopt"
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
  "name": "mptcp_setsockopt_v6",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592003537,
      "name": "mptcp_setsockopt_v6",
      "external": false,
      "loc": "net/mptcp/sockopt.c:382",
      "file": "net/mptcp/sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_setsockopt"
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
  "name": "mptcp_setsockopt_v6",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593741359,
      "name": "mptcp_setsockopt_v6",
      "external": false,
      "loc": "net/mptcp/sockopt.c:386",
      "file": "net/mptcp/sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_setsockopt"
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
  "name": "mptcp_setsockopt_v6",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595677839,
      "name": "mptcp_setsockopt_v6",
      "external": false,
      "loc": "net/mptcp/sockopt.c:386",
      "file": "net/mptcp/sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_setsockopt"
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
  "name": "mptcp_setsockopt_v6",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596188247,
      "name": "mptcp_setsockopt_v6",
      "external": false,
      "loc": "net/mptcp/sockopt.c:388",
      "file": "net/mptcp/sockopt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_setsockopt"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int mptcp_setsockopt_v6(struct mptcp_sock * msk, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt_v6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597053520,
      "name": "mptcp_setsockopt_v6",
      "external": false,
      "loc": "net/mptcp/sockopt.c:389",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sockopt.c:mptcp_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597053520,
      "name": "mptcp_setsockopt_v6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
int mptcp_setsockopt_v6(struct mptcp_sock * msk, int optname, sockptr_t optval, unsigned int optlen)
```
</details>
</li>
</ul>
