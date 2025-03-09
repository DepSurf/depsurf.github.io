# Function: <code>__mptcp_expand_seq</code>

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
u64 __mptcp_expand_seq(u64 old_seq, u64 cur_seq)
```

```json
{
  "name": "__mptcp_expand_seq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591123730,
      "name": "__mptcp_expand_seq",
      "external": true,
      "loc": "net/mptcp/options.c:896",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_incoming_options"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591122832,
      "name": "__mptcp_expand_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
u64 __mptcp_expand_seq(u64 old_seq, u64 cur_seq)
```

```json
{
  "name": "__mptcp_expand_seq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591970954,
      "name": "__mptcp_expand_seq",
      "external": true,
      "loc": "net/mptcp/options.c:978",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:mptcp_incoming_options"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591969952,
      "name": "__mptcp_expand_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
u64 __mptcp_expand_seq(u64 old_seq, u64 cur_seq)
```

```json
{
  "name": "__mptcp_expand_seq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593696128,
      "name": "__mptcp_expand_seq",
      "external": true,
      "loc": "net/mptcp/options.c:1004",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:ack_update_msk"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593699072,
      "name": "__mptcp_expand_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
u64 __mptcp_expand_seq(u64 old_seq, u64 cur_seq)
```

```json
{
  "name": "__mptcp_expand_seq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595629696,
      "name": "__mptcp_expand_seq",
      "external": true,
      "loc": "net/mptcp/options.c:1013",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:ack_update_msk"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595632752,
      "name": "__mptcp_expand_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
u64 __mptcp_expand_seq(u64 old_seq, u64 cur_seq)
```

```json
{
  "name": "__mptcp_expand_seq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596138816,
      "name": "__mptcp_expand_seq",
      "external": true,
      "loc": "net/mptcp/options.c:1013",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:ack_update_msk"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596141136,
      "name": "__mptcp_expand_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
u64 __mptcp_expand_seq(u64 old_seq, u64 cur_seq)
```

```json
{
  "name": "__mptcp_expand_seq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597012528,
      "name": "__mptcp_expand_seq",
      "external": true,
      "loc": "net/mptcp/options.c:1015",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:ack_update_msk"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597014848,
      "name": "__mptcp_expand_seq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
u64 __mptcp_expand_seq(u64 old_seq, u64 cur_seq)
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
