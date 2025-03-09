# Function: <code>__mptcp_clean_una</code>

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
void __mptcp_clean_una(struct sock * sk)
```

```json
{
  "name": "__mptcp_clean_una",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591151952,
      "name": "__mptcp_clean_una",
      "external": false,
      "loc": "net/mptcp/protocol.c:990",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591151952,
      "name": "__mptcp_clean_una",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
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
void __mptcp_clean_una(struct sock * sk)
```

```json
{
  "name": "__mptcp_clean_una",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591084288,
      "name": "__mptcp_clean_una",
      "external": false,
      "loc": "net/mptcp/protocol.c:1033",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:__mptcp_retrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591084288,
      "name": "__mptcp_clean_una",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1092
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __mptcp_clean_una(struct sock * sk)
```

```json
{
  "name": "__mptcp_clean_una",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_clean_una",
      "external": false,
      "loc": "net/mptcp/protocol.c:1050",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:__mptcp_retrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591925824,
      "name": "__mptcp_clean_una",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1186
    },
    {
      "addr": 18446744071592752223,
      "name": "__mptcp_clean_una.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void __mptcp_clean_una(struct sock * sk)
```

```json
{
  "name": "__mptcp_clean_una",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_clean_una",
      "external": false,
      "loc": "net/mptcp/protocol.c:1009",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_retransmit_pending_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593646720,
      "name": "__mptcp_clean_una",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    },
    {
      "addr": 18446744071594639072,
      "name": "__mptcp_clean_una.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void __mptcp_clean_una(struct sock * sk)
```

```json
{
  "name": "__mptcp_clean_una",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_clean_una",
      "external": false,
      "loc": "net/mptcp/protocol.c:982",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_retransmit_pending_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595577248,
      "name": "__mptcp_clean_una",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
    },
    {
      "addr": 18446744071596368354,
      "name": "__mptcp_clean_una.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __mptcp_clean_una(struct sock * sk)
```

```json
{
  "name": "__mptcp_clean_una",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_clean_una",
      "external": false,
      "loc": "net/mptcp/protocol.c:959",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_retransmit_pending_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596087232,
      "name": "__mptcp_clean_una",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 756
    },
    {
      "addr": 18446744071596898212,
      "name": "__mptcp_clean_una.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __mptcp_clean_una(struct sock * sk)
```

```json
{
  "name": "__mptcp_clean_una",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_clean_una",
      "external": false,
      "loc": "net/mptcp/protocol.c:988",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:__mptcp_data_acked",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_retransmit_pending_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596955968,
      "name": "__mptcp_clean_una",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 756
    },
    {
      "addr": 18446744071597823337,
      "name": "__mptcp_clean_una.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __mptcp_clean_una(struct sock * sk)
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
