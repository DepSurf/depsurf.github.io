# Function: <code>mptcp_update_rcv_data_fin</code>

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
bool mptcp_update_rcv_data_fin(struct mptcp_sock * msk, u64 data_fin_seq, bool use_64bit)
```

```json
{
  "name": "mptcp_update_rcv_data_fin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591187138,
      "name": "mptcp_update_rcv_data_fin",
      "external": true,
      "loc": "net/mptcp/options.c:898",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_incoming_options"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591186496,
      "name": "mptcp_update_rcv_data_fin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool mptcp_update_rcv_data_fin(struct mptcp_sock * msk, u64 data_fin_seq, bool use_64bit)
```

```json
{
  "name": "mptcp_update_rcv_data_fin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591123710,
      "name": "mptcp_update_rcv_data_fin",
      "external": true,
      "loc": "net/mptcp/options.c:953",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_incoming_options"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591122912,
      "name": "mptcp_update_rcv_data_fin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool mptcp_update_rcv_data_fin(struct mptcp_sock * msk, u64 data_fin_seq, bool use_64bit)
```

```json
{
  "name": "mptcp_update_rcv_data_fin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591970082,
      "name": "mptcp_update_rcv_data_fin",
      "external": true,
      "loc": "net/mptcp/options.c:1035",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592754721,
      "name": "mptcp_update_rcv_data_fin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071591970032,
      "name": "mptcp_update_rcv_data_fin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool mptcp_update_rcv_data_fin(struct mptcp_sock * msk, u64 data_fin_seq, bool use_64bit)
```

```json
{
  "name": "mptcp_update_rcv_data_fin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593699234,
      "name": "mptcp_update_rcv_data_fin",
      "external": true,
      "loc": "net/mptcp/options.c:1061",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594641747,
      "name": "mptcp_update_rcv_data_fin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071593699184,
      "name": "mptcp_update_rcv_data_fin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool mptcp_update_rcv_data_fin(struct mptcp_sock * msk, u64 data_fin_seq, bool use_64bit)
```

```json
{
  "name": "mptcp_update_rcv_data_fin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595632930,
      "name": "mptcp_update_rcv_data_fin",
      "external": true,
      "loc": "net/mptcp/options.c:1070",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596371138,
      "name": "mptcp_update_rcv_data_fin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071595632880,
      "name": "mptcp_update_rcv_data_fin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool mptcp_update_rcv_data_fin(struct mptcp_sock * msk, u64 data_fin_seq, bool use_64bit)
```

```json
{
  "name": "mptcp_update_rcv_data_fin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596141314,
      "name": "mptcp_update_rcv_data_fin",
      "external": true,
      "loc": "net/mptcp/options.c:1076",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596900452,
      "name": "mptcp_update_rcv_data_fin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071596141264,
      "name": "mptcp_update_rcv_data_fin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool mptcp_update_rcv_data_fin(struct mptcp_sock * msk, u64 data_fin_seq, bool use_64bit)
```

```json
{
  "name": "mptcp_update_rcv_data_fin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597015026,
      "name": "mptcp_update_rcv_data_fin",
      "external": true,
      "loc": "net/mptcp/options.c:1078",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597825658,
      "name": "mptcp_update_rcv_data_fin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071597014976,
      "name": "mptcp_update_rcv_data_fin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
bool mptcp_update_rcv_data_fin(struct mptcp_sock * msk, u64 data_fin_seq, bool use_64bit)
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
