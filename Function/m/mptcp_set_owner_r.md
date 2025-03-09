# Function: <code>mptcp_set_owner_r</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void mptcp_set_owner_r(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "mptcp_set_owner_r",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593642704,
      "name": "mptcp_set_owner_r",
      "external": false,
      "loc": "net/mptcp/protocol.c:197",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593642704,
      "name": "mptcp_set_owner_r",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void mptcp_set_owner_r(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "mptcp_set_owner_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595583552,
      "name": "mptcp_set_owner_r",
      "external": true,
      "loc": "net/mptcp/protocol.c:194",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595583552,
      "name": "mptcp_set_owner_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void mptcp_set_owner_r(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "mptcp_set_owner_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596093216,
      "name": "mptcp_set_owner_r",
      "external": true,
      "loc": "net/mptcp/protocol.c:208",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596093216,
      "name": "mptcp_set_owner_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void mptcp_set_owner_r(struct sk_buff * skb, struct sock * sk)
```

```json
{
  "name": "mptcp_set_owner_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596962160,
      "name": "mptcp_set_owner_r",
      "external": true,
      "loc": "net/mptcp/protocol.c:196",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596962160,
      "name": "mptcp_set_owner_r",
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void mptcp_set_owner_r(struct sk_buff * skb, struct sock * sk)
```
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
