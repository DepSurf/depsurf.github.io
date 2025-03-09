# Function: <code>mptcp_pending_data_fin</code>

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
  "name": "mptcp_pending_data_fin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591160025,
      "name": "mptcp_pending_data_fin",
      "external": false,
      "loc": "net/mptcp/protocol.c:381",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_data_ready",
        "net/mptcp/protocol.c:mptcp_data_ready"
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
  "name": "mptcp_pending_data_fin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591094051,
      "name": "mptcp_pending_data_fin",
      "external": false,
      "loc": "net/mptcp/protocol.c:377",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_data_ready",
        "net/mptcp/protocol.c:mptcp_data_ready"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool mptcp_pending_data_fin(struct sock * sk, u64 * seq)
```

```json
{
  "name": "mptcp_pending_data_fin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591917411,
      "name": "mptcp_pending_data_fin",
      "external": false,
      "loc": "net/mptcp/protocol.c:386",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591917328,
      "name": "mptcp_pending_data_fin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071592751729,
      "name": "mptcp_pending_data_fin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
bool mptcp_pending_data_fin(struct sock * sk, u64 * seq)
```

```json
{
  "name": "mptcp_pending_data_fin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pending_data_fin",
      "external": false,
      "loc": "net/mptcp/protocol.c:450",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593641264,
      "name": "mptcp_pending_data_fin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071594638494,
      "name": "mptcp_pending_data_fin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
bool mptcp_pending_data_fin(struct sock * sk, u64 * seq)
```

```json
{
  "name": "mptcp_pending_data_fin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_pending_data_fin",
      "external": false,
      "loc": "net/mptcp/protocol.c:442",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595572272,
      "name": "mptcp_pending_data_fin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071596367940,
      "name": "mptcp_pending_data_fin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
bool mptcp_pending_data_fin(struct sock * sk, u64 * seq)
```

```json
{
  "name": "mptcp_pending_data_fin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596086581,
      "name": "mptcp_pending_data_fin",
      "external": false,
      "loc": "net/mptcp/protocol.c:456",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596081424,
      "name": "mptcp_pending_data_fin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071596897718,
      "name": "mptcp_pending_data_fin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
bool mptcp_pending_data_fin(struct sock * sk, u64 * seq)
```

```json
{
  "name": "mptcp_pending_data_fin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596960389,
      "name": "mptcp_pending_data_fin",
      "external": false,
      "loc": "net/mptcp/protocol.c:444",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596949680,
      "name": "mptcp_pending_data_fin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071597823041,
      "name": "mptcp_pending_data_fin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
bool mptcp_pending_data_fin(struct sock * sk, u64 * seq)
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
