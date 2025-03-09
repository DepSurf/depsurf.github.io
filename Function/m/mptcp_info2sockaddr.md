# Function: <code>mptcp_info2sockaddr</code>

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
  "name": "mptcp_info2sockaddr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591099840,
      "name": "mptcp_info2sockaddr",
      "external": false,
      "loc": "net/mptcp/subflow.c:949",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:__mptcp_subflow_connect"
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
  "name": "mptcp_info2sockaddr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591180587,
      "name": "mptcp_info2sockaddr",
      "external": false,
      "loc": "net/mptcp/subflow.c:1119",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:__mptcp_subflow_connect"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mptcp_info2sockaddr(const struct mptcp_addr_info * info, struct __kernel_sockaddr_storage * addr, short unsigned int family)
```

```json
{
  "name": "mptcp_info2sockaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591115472,
      "name": "mptcp_info2sockaddr",
      "external": true,
      "loc": "net/mptcp/subflow.c:1221",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591115472,
      "name": "mptcp_info2sockaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void mptcp_info2sockaddr(const struct mptcp_addr_info * info, struct __kernel_sockaddr_storage * addr, short unsigned int family)
```

```json
{
  "name": "mptcp_info2sockaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591961120,
      "name": "mptcp_info2sockaddr",
      "external": true,
      "loc": "net/mptcp/subflow.c:1348",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591961120,
      "name": "mptcp_info2sockaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void mptcp_info2sockaddr(const struct mptcp_addr_info * info, struct __kernel_sockaddr_storage * addr, short unsigned int family)
```

```json
{
  "name": "mptcp_info2sockaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593688864,
      "name": "mptcp_info2sockaddr",
      "external": true,
      "loc": "net/mptcp/subflow.c:1436",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593688864,
      "name": "mptcp_info2sockaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void mptcp_info2sockaddr(const struct mptcp_addr_info * info, struct __kernel_sockaddr_storage * addr, short unsigned int family)
```

```json
{
  "name": "mptcp_info2sockaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595622000,
      "name": "mptcp_info2sockaddr",
      "external": true,
      "loc": "net/mptcp/subflow.c:1508",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595622000,
      "name": "mptcp_info2sockaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void mptcp_info2sockaddr(const struct mptcp_addr_info * info, struct __kernel_sockaddr_storage * addr, short unsigned int family)
```

```json
{
  "name": "mptcp_info2sockaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596130320,
      "name": "mptcp_info2sockaddr",
      "external": true,
      "loc": "net/mptcp/subflow.c:1488",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596130320,
      "name": "mptcp_info2sockaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void mptcp_info2sockaddr(const struct mptcp_addr_info * info, struct __kernel_sockaddr_storage * addr, short unsigned int family)
```

```json
{
  "name": "mptcp_info2sockaddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597004000,
      "name": "mptcp_info2sockaddr",
      "external": true,
      "loc": "net/mptcp/subflow.c:1485",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597004000,
      "name": "mptcp_info2sockaddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void mptcp_info2sockaddr(const struct mptcp_addr_info * info, struct __kernel_sockaddr_storage * addr, short unsigned int family)
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
