# Function: <code>mptcp_can_accept_new_subflow</code>

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
  "name": "mptcp_can_accept_new_subflow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591173297,
      "name": "mptcp_can_accept_new_subflow",
      "external": false,
      "loc": "net/mptcp/subflow.c:57",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:mptcp_subflow_init_cookie_req",
        "net/mptcp/subflow.c:subflow_check_req"
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
  "name": "mptcp_can_accept_new_subflow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591110068,
      "name": "mptcp_can_accept_new_subflow",
      "external": false,
      "loc": "net/mptcp/subflow.c:62",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_check_req"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool mptcp_can_accept_new_subflow(const struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_can_accept_new_subflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_can_accept_new_subflow",
      "external": false,
      "loc": "net/mptcp/subflow.c:62",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591950464,
      "name": "mptcp_can_accept_new_subflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071592753502,
      "name": "mptcp_can_accept_new_subflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
bool mptcp_can_accept_new_subflow(const struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_can_accept_new_subflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_can_accept_new_subflow",
      "external": false,
      "loc": "net/mptcp/subflow.c:62",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593677344,
      "name": "mptcp_can_accept_new_subflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071594640485,
      "name": "mptcp_can_accept_new_subflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool mptcp_can_accept_new_subflow(const struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_can_accept_new_subflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_can_accept_new_subflow",
      "external": false,
      "loc": "net/mptcp/subflow.c:61",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595609664,
      "name": "mptcp_can_accept_new_subflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071596369951,
      "name": "mptcp_can_accept_new_subflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool mptcp_can_accept_new_subflow(const struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_can_accept_new_subflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_can_accept_new_subflow",
      "external": false,
      "loc": "net/mptcp/subflow.c:62",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596118288,
      "name": "mptcp_can_accept_new_subflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071596899229,
      "name": "mptcp_can_accept_new_subflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
bool mptcp_can_accept_new_subflow(const struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_can_accept_new_subflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_can_accept_new_subflow",
      "external": false,
      "loc": "net/mptcp/subflow.c:62",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596991840,
      "name": "mptcp_can_accept_new_subflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071597824619,
      "name": "mptcp_can_accept_new_subflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool mptcp_can_accept_new_subflow(const struct mptcp_sock * msk)
```
</details>
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
