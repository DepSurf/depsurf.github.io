# Function: <code>mptcp_setsockopt_sol_tcp_congestion</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int mptcp_setsockopt_sol_tcp_congestion(struct mptcp_sock * msk, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt_sol_tcp_congestion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_setsockopt_sol_tcp_congestion",
      "external": false,
      "loc": "net/mptcp/sockopt.c:513",
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
      "addr": 18446744071591148656,
      "name": "mptcp_setsockopt_sol_tcp_congestion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 794
    },
    {
      "addr": 18446744071591584537,
      "name": "mptcp_setsockopt_sol_tcp_congestion.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int mptcp_setsockopt_sol_tcp_congestion(struct mptcp_sock * msk, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt_sol_tcp_congestion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_setsockopt_sol_tcp_congestion",
      "external": false,
      "loc": "net/mptcp/sockopt.c:555",
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
      "addr": 18446744071591999472,
      "name": "mptcp_setsockopt_sol_tcp_congestion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
    },
    {
      "addr": 18446744071592755301,
      "name": "mptcp_setsockopt_sol_tcp_congestion.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int mptcp_setsockopt_sol_tcp_congestion(struct mptcp_sock * msk, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt_sol_tcp_congestion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_setsockopt_sol_tcp_congestion",
      "external": false,
      "loc": "net/mptcp/sockopt.c:577",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593733728,
      "name": "mptcp_setsockopt_sol_tcp_congestion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    },
    {
      "addr": 18446744071594642357,
      "name": "mptcp_setsockopt_sol_tcp_congestion.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int mptcp_setsockopt_sol_tcp_congestion(struct mptcp_sock * msk, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt_sol_tcp_congestion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595671248,
      "name": "mptcp_setsockopt_sol_tcp_congestion",
      "external": false,
      "loc": "net/mptcp/sockopt.c:578",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595671248,
      "name": "mptcp_setsockopt_sol_tcp_congestion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
int mptcp_setsockopt_sol_tcp_congestion(struct mptcp_sock * msk, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt_sol_tcp_congestion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596180416,
      "name": "mptcp_setsockopt_sol_tcp_congestion",
      "external": false,
      "loc": "net/mptcp/sockopt.c:580",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596180416,
      "name": "mptcp_setsockopt_sol_tcp_congestion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
int mptcp_setsockopt_sol_tcp_congestion(struct mptcp_sock * msk, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt_sol_tcp_congestion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597055920,
      "name": "mptcp_setsockopt_sol_tcp_congestion",
      "external": false,
      "loc": "net/mptcp/sockopt.c:584",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597055920,
      "name": "mptcp_setsockopt_sol_tcp_congestion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int mptcp_setsockopt_sol_tcp_congestion(struct mptcp_sock * msk, sockptr_t optval, unsigned int optlen)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
