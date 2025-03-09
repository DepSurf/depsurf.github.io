# Function: <code>mptcp_subflow_data_available</code>

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
bool mptcp_subflow_data_available(struct sock * sk)
```

```json
{
  "name": "mptcp_subflow_data_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591098368,
      "name": "mptcp_subflow_data_available",
      "external": true,
      "loc": "net/mptcp/subflow.c:844",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591098368,
      "name": "mptcp_subflow_data_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
bool mptcp_subflow_data_available(struct sock * sk)
```

```json
{
  "name": "mptcp_subflow_data_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591178240,
      "name": "mptcp_subflow_data_available",
      "external": true,
      "loc": "net/mptcp/subflow.c:981",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591178240,
      "name": "mptcp_subflow_data_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
bool mptcp_subflow_data_available(struct sock * sk)
```

```json
{
  "name": "mptcp_subflow_data_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591114080,
      "name": "mptcp_subflow_data_available",
      "external": true,
      "loc": "net/mptcp/subflow.c:1078",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591114080,
      "name": "mptcp_subflow_data_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
bool mptcp_subflow_data_available(struct sock * sk)
```

```json
{
  "name": "mptcp_subflow_data_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591959664,
      "name": "mptcp_subflow_data_available",
      "external": true,
      "loc": "net/mptcp/subflow.c:1205",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591959664,
      "name": "mptcp_subflow_data_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool mptcp_subflow_data_available(struct sock * sk)
```

```json
{
  "name": "mptcp_subflow_data_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593687024,
      "name": "mptcp_subflow_data_available",
      "external": true,
      "loc": "net/mptcp/subflow.c:1294",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready",
        "net/mptcp/subflow.c:subflow_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593687024,
      "name": "mptcp_subflow_data_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
bool mptcp_subflow_data_available(struct sock * sk)
```

```json
{
  "name": "mptcp_subflow_data_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595620016,
      "name": "mptcp_subflow_data_available",
      "external": true,
      "loc": "net/mptcp/subflow.c:1358",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595620016,
      "name": "mptcp_subflow_data_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
bool mptcp_subflow_data_available(struct sock * sk)
```

```json
{
  "name": "mptcp_subflow_data_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596128128,
      "name": "mptcp_subflow_data_available",
      "external": true,
      "loc": "net/mptcp/subflow.c:1329",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596128128,
      "name": "mptcp_subflow_data_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
bool mptcp_subflow_data_available(struct sock * sk)
```

```json
{
  "name": "mptcp_subflow_data_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597002256,
      "name": "mptcp_subflow_data_available",
      "external": true,
      "loc": "net/mptcp/subflow.c:1354",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597002256,
      "name": "mptcp_subflow_data_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
bool mptcp_subflow_data_available(struct sock * sk)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
