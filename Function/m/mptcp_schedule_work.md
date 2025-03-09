# Function: <code>mptcp_schedule_work</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mptcp_schedule_work(struct sock * sk)
```

```json
{
  "name": "mptcp_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591159568,
      "name": "mptcp_schedule_work",
      "external": true,
      "loc": "net/mptcp/protocol.c:762",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_subflow_eof",
        "net/mptcp/protocol.c:mptcp_data_ready",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591159568,
      "name": "mptcp_schedule_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mptcp_schedule_work(struct sock * sk)
```

```json
{
  "name": "mptcp_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591093440,
      "name": "mptcp_schedule_work",
      "external": true,
      "loc": "net/mptcp/protocol.c:795",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_subflow_eof",
        "net/mptcp/protocol.c:__mptcp_flush_join_list",
        "net/mptcp/protocol.c:mptcp_data_ready",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591093440,
      "name": "mptcp_schedule_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
bool mptcp_schedule_work(struct sock * sk)
```

```json
{
  "name": "mptcp_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591933888,
      "name": "mptcp_schedule_work",
      "external": true,
      "loc": "net/mptcp/protocol.c:814",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_subflow_eof",
        "net/mptcp/protocol.c:mptcp_data_ready",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591933888,
      "name": "mptcp_schedule_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
bool mptcp_schedule_work(struct sock * sk)
```

```json
{
  "name": "mptcp_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593659232,
      "name": "mptcp_schedule_work",
      "external": true,
      "loc": "net/mptcp/protocol.c:875",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_subflow_eof",
        "net/mptcp/protocol.c:mptcp_data_ready",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593659232,
      "name": "mptcp_schedule_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
bool mptcp_schedule_work(struct sock * sk)
```

```json
{
  "name": "mptcp_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595589536,
      "name": "mptcp_schedule_work",
      "external": true,
      "loc": "net/mptcp/protocol.c:867",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_subflow_eof",
        "net/mptcp/protocol.c:mptcp_data_ready",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595589536,
      "name": "mptcp_schedule_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
bool mptcp_schedule_work(struct sock * sk)
```

```json
{
  "name": "mptcp_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596098768,
      "name": "mptcp_schedule_work",
      "external": true,
      "loc": "net/mptcp/protocol.c:888",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_timeout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_data_ready",
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596098768,
      "name": "mptcp_schedule_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
bool mptcp_schedule_work(struct sock * sk)
```

```json
{
  "name": "mptcp_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596968048,
      "name": "mptcp_schedule_work",
      "external": true,
      "loc": "net/mptcp/protocol.c:917",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_tout_timer",
        "net/mptcp/protocol.c:mptcp_retransmit_timer",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_data_ready",
        "net/mptcp/subflow.c:subflow_ulp_release",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:mptcp_subflow_reset",
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596968048,
      "name": "mptcp_schedule_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
bool mptcp_schedule_work(struct sock * sk)
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
