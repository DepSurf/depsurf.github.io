# Function: <code>mptcp_pm_new_connection</code>

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
void mptcp_pm_new_connection(struct mptcp_sock * msk, int server_side)
```

```json
{
  "name": "mptcp_pm_new_connection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591109824,
      "name": "mptcp_pm_new_connection",
      "external": true,
      "loc": "net/mptcp/pm.c:39",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_connect",
        "net/mptcp/subflow.c:subflow_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591109824,
      "name": "mptcp_pm_new_connection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void mptcp_pm_new_connection(struct mptcp_sock * msk, int server_side)
```

```json
{
  "name": "mptcp_pm_new_connection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591192480,
      "name": "mptcp_pm_new_connection",
      "external": true,
      "loc": "net/mptcp/pm.c:71",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_connect",
        "net/mptcp/subflow.c:subflow_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591192480,
      "name": "mptcp_pm_new_connection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void mptcp_pm_new_connection(struct mptcp_sock * msk, const struct sock * ssk, int server_side)
```

```json
{
  "name": "mptcp_pm_new_connection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591129872,
      "name": "mptcp_pm_new_connection",
      "external": true,
      "loc": "net/mptcp/pm.c:72",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_connect",
        "net/mptcp/subflow.c:subflow_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591129872,
      "name": "mptcp_pm_new_connection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void mptcp_pm_new_connection(struct mptcp_sock * msk, const struct sock * ssk, int server_side)
```

```json
{
  "name": "mptcp_pm_new_connection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591978544,
      "name": "mptcp_pm_new_connection",
      "external": true,
      "loc": "net/mptcp/pm.c:74",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_connect",
        "net/mptcp/subflow.c:subflow_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591978544,
      "name": "mptcp_pm_new_connection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void mptcp_pm_new_connection(struct mptcp_sock * msk, const struct sock * ssk, int server_side)
```

```json
{
  "name": "mptcp_pm_new_connection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593708176,
      "name": "mptcp_pm_new_connection",
      "external": true,
      "loc": "net/mptcp/pm.c:74",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_connect",
        "net/mptcp/subflow.c:subflow_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593708176,
      "name": "mptcp_pm_new_connection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void mptcp_pm_new_connection(struct mptcp_sock * msk, const struct sock * ssk, int server_side)
```

```json
{
  "name": "mptcp_pm_new_connection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595642368,
      "name": "mptcp_pm_new_connection",
      "external": true,
      "loc": "net/mptcp/pm.c:74",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_connect",
        "net/mptcp/subflow.c:subflow_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595642368,
      "name": "mptcp_pm_new_connection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void mptcp_pm_new_connection(struct mptcp_sock * msk, const struct sock * ssk, int server_side)
```

```json
{
  "name": "mptcp_pm_new_connection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596150704,
      "name": "mptcp_pm_new_connection",
      "external": true,
      "loc": "net/mptcp/pm.c:76",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_connect",
        "net/mptcp/subflow.c:subflow_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596150704,
      "name": "mptcp_pm_new_connection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void mptcp_pm_new_connection(struct mptcp_sock * msk, const struct sock * ssk, int server_side)
```

```json
{
  "name": "mptcp_pm_new_connection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597024720,
      "name": "mptcp_pm_new_connection",
      "external": true,
      "loc": "net/mptcp/pm.c:76",
      "file": "net/mptcp/pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_connect",
        "net/mptcp/subflow.c:subflow_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597024720,
      "name": "mptcp_pm_new_connection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void mptcp_pm_new_connection(struct mptcp_sock * msk, int server_side)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sock * ssk</code>
</li>
<li>
<b>Param reordered. </b>
<code>msk, server_side</code> ➡️ <code>msk, ssk, server_side</code>
</li>
</ul>
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
