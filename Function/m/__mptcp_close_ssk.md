# Function: <code>__mptcp_close_ssk</code>

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
  "name": "__mptcp_close_ssk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591079992,
      "name": "__mptcp_close_ssk",
      "external": false,
      "loc": "net/mptcp/protocol.c:1156",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_close"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "__mptcp_close_ssk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591161248,
      "name": "__mptcp_close_ssk",
      "external": true,
      "loc": "net/mptcp/protocol.c:2124",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_subflow_received",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_received"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591161248,
      "name": "__mptcp_close_ssk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
void __mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "__mptcp_close_ssk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591082752,
      "name": "__mptcp_close_ssk",
      "external": false,
      "loc": "net/mptcp/protocol.c:2178",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591082752,
      "name": "__mptcp_close_ssk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void __mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "__mptcp_close_ssk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591942176,
      "name": "__mptcp_close_ssk",
      "external": false,
      "loc": "net/mptcp/protocol.c:2238",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_destroy_sock",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591942176,
      "name": "__mptcp_close_ssk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
void __mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow, unsigned int flags)
```

```json
{
  "name": "__mptcp_close_ssk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593667728,
      "name": "__mptcp_close_ssk",
      "external": false,
      "loc": "net/mptcp/protocol.c:2304",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593667728,
      "name": "__mptcp_close_ssk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
void __mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow, unsigned int flags)
```

```json
{
  "name": "__mptcp_close_ssk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595596240,
      "name": "__mptcp_close_ssk",
      "external": false,
      "loc": "net/mptcp/protocol.c:2315",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595596240,
      "name": "__mptcp_close_ssk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
void __mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow, unsigned int flags)
```

```json
{
  "name": "__mptcp_close_ssk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596105424,
      "name": "__mptcp_close_ssk",
      "external": false,
      "loc": "net/mptcp/protocol.c:2306",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_unaccepted_force_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596105424,
      "name": "__mptcp_close_ssk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
void __mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow, unsigned int flags)
```

```json
{
  "name": "__mptcp_close_ssk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_close_ssk",
      "external": false,
      "loc": "net/mptcp/protocol.c:2385",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_unaccepted_force_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596975200,
      "name": "__mptcp_close_ssk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1420
    },
    {
      "addr": 18446744071597824252,
      "name": "__mptcp_close_ssk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
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
