# Function: <code>mptcp_subflow_discard_data</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void mptcp_subflow_discard_data(struct sock * ssk, struct sk_buff * skb, u64 limit)
```

```json
{
  "name": "mptcp_subflow_discard_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591171104,
      "name": "mptcp_subflow_discard_data",
      "external": false,
      "loc": "net/mptcp/subflow.c:875",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591171104,
      "name": "mptcp_subflow_discard_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_subflow_discard_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591112241,
      "name": "mptcp_subflow_discard_data",
      "external": false,
      "loc": "net/mptcp/subflow.c:957",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_subflow_discard_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591957495,
      "name": "mptcp_subflow_discard_data",
      "external": false,
      "loc": "net/mptcp/subflow.c:1070",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_subflow_discard_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593684842,
      "name": "mptcp_subflow_discard_data",
      "external": false,
      "loc": "net/mptcp/subflow.c:1115",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_subflow_discard_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595616172,
      "name": "mptcp_subflow_discard_data",
      "external": false,
      "loc": "net/mptcp/subflow.c:1187",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_subflow_discard_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596124342,
      "name": "mptcp_subflow_discard_data",
      "external": false,
      "loc": "net/mptcp/subflow.c:1163",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_subflow_discard_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596997915,
      "name": "mptcp_subflow_discard_data",
      "external": false,
      "loc": "net/mptcp/subflow.c:1188",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void mptcp_subflow_discard_data(struct sock * ssk, struct sk_buff * skb, u64 limit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void mptcp_subflow_discard_data(struct sock * ssk, struct sk_buff * skb, u64 limit)
```
</details>
</li>
</ul>
