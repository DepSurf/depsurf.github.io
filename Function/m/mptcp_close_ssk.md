# Function: <code>mptcp_close_ssk</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "mptcp_close_ssk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591101322,
      "name": "mptcp_close_ssk",
      "external": true,
      "loc": "net/mptcp/protocol.c:2222",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_worker"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591095648,
      "name": "mptcp_close_ssk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "mptcp_close_ssk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591944749,
      "name": "mptcp_close_ssk",
      "external": true,
      "loc": "net/mptcp/protocol.c:2287",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_worker"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591944064,
      "name": "mptcp_close_ssk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "mptcp_close_ssk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593670155,
      "name": "mptcp_close_ssk",
      "external": true,
      "loc": "net/mptcp/protocol.c:2371",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_worker"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593668432,
      "name": "mptcp_close_ssk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "mptcp_close_ssk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595598685,
      "name": "mptcp_close_ssk",
      "external": true,
      "loc": "net/mptcp/protocol.c:2384",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_worker"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595596992,
      "name": "mptcp_close_ssk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "mptcp_close_ssk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596108384,
      "name": "mptcp_close_ssk",
      "external": true,
      "loc": "net/mptcp/protocol.c:2393",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_worker"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow",
        "net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596106192,
      "name": "mptcp_close_ssk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "mptcp_close_ssk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596979443,
      "name": "mptcp_close_ssk",
      "external": true,
      "loc": "net/mptcp/protocol.c:2478",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_worker"
      ],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow",
        "net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596976640,
      "name": "mptcp_close_ssk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void mptcp_close_ssk(struct sock * sk, struct sock * ssk, struct mptcp_subflow_context * subflow)
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
