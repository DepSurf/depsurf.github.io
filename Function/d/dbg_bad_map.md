# Function: <code>dbg_bad_map</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dbg_bad_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591111201,
      "name": "dbg_bad_map",
      "external": false,
      "loc": "net/mptcp/subflow.c:790",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dbg_bad_map(struct mptcp_subflow_context * subflow, u32 ssn)
```

```json
{
  "name": "dbg_bad_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591949696,
      "name": "dbg_bad_map",
      "external": false,
      "loc": "net/mptcp/subflow.c:804",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591949696,
      "name": "dbg_bad_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void dbg_bad_map(struct mptcp_subflow_context * subflow, u32 ssn)
```

```json
{
  "name": "dbg_bad_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593677216,
      "name": "dbg_bad_map",
      "external": false,
      "loc": "net/mptcp/subflow.c:851",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593677216,
      "name": "dbg_bad_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dbg_bad_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595614343,
      "name": "dbg_bad_map",
      "external": false,
      "loc": "net/mptcp/subflow.c:923",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status"
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
  "name": "dbg_bad_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596122731,
      "name": "dbg_bad_map",
      "external": false,
      "loc": "net/mptcp/subflow.c:899",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status"
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
  "name": "dbg_bad_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596996299,
      "name": "dbg_bad_map",
      "external": false,
      "loc": "net/mptcp/subflow.c:924",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void dbg_bad_map(struct mptcp_subflow_context * subflow, u32 ssn)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void dbg_bad_map(struct mptcp_subflow_context * subflow, u32 ssn)
```
</details>
</li>
</ul>
