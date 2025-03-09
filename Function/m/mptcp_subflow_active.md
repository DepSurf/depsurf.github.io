# Function: <code>mptcp_subflow_active</code>

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
  "name": "mptcp_subflow_active",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591167058,
      "name": "mptcp_subflow_active",
      "external": false,
      "loc": "net/mptcp/protocol.c:411",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:mptcp_subflow_get_send"
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
  "name": "mptcp_subflow_active",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591089616,
      "name": "mptcp_subflow_active",
      "external": false,
      "loc": "net/mptcp/protocol.h:555",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send"
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
bool mptcp_subflow_active(struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "mptcp_subflow_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_subflow_active",
      "external": true,
      "loc": "net/mptcp/protocol.c:1417",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592752897,
      "name": "mptcp_subflow_active.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071591935024,
      "name": "mptcp_subflow_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
bool mptcp_subflow_active(struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "mptcp_subflow_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_subflow_active",
      "external": true,
      "loc": "net/mptcp/protocol.c:1418",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594639830,
      "name": "mptcp_subflow_active.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593660144,
      "name": "mptcp_subflow_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
bool mptcp_subflow_active(struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "mptcp_subflow_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_subflow_active",
      "external": true,
      "loc": "net/mptcp/protocol.c:1379",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596369072,
      "name": "mptcp_subflow_active.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071595590544,
      "name": "mptcp_subflow_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
bool mptcp_subflow_active(struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "mptcp_subflow_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_subflow_active",
      "external": true,
      "loc": "net/mptcp/protocol.c:1350",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596898678,
      "name": "mptcp_subflow_active.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071596099712,
      "name": "mptcp_subflow_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
bool mptcp_subflow_active(struct mptcp_subflow_context * subflow)
```

```json
{
  "name": "mptcp_subflow_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_subflow_active",
      "external": true,
      "loc": "net/mptcp/protocol.c:1379",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597823795,
      "name": "mptcp_subflow_active.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071596969120,
      "name": "mptcp_subflow_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
bool mptcp_subflow_active(struct mptcp_subflow_context * subflow)
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
