# Function: <code>__mptcp_subflow_push_pending</code>

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
void __mptcp_subflow_push_pending(struct sock * sk, struct sock * ssk)
```

```json
{
  "name": "__mptcp_subflow_push_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591160128,
      "name": "__mptcp_subflow_push_pending",
      "external": false,
      "loc": "net/mptcp/protocol.c:1522",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591160128,
      "name": "__mptcp_subflow_push_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 841
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
void __mptcp_subflow_push_pending(struct sock * sk, struct sock * ssk)
```

```json
{
  "name": "__mptcp_subflow_push_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591094544,
      "name": "__mptcp_subflow_push_pending",
      "external": false,
      "loc": "net/mptcp/protocol.c:1557",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated",
        "net/mptcp/protocol.c:__mptcp_check_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591094544,
      "name": "__mptcp_subflow_push_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1063
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
void __mptcp_subflow_push_pending(struct sock * sk, struct sock * ssk)
```

```json
{
  "name": "__mptcp_subflow_push_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_subflow_push_pending",
      "external": false,
      "loc": "net/mptcp/protocol.c:1600",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated",
        "net/mptcp/protocol.c:__mptcp_check_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591937216,
      "name": "__mptcp_subflow_push_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
    },
    {
      "addr": 18446744071592753138,
      "name": "__mptcp_subflow_push_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void __mptcp_subflow_push_pending(struct sock * sk, struct sock * ssk)
```

```json
{
  "name": "__mptcp_subflow_push_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_subflow_push_pending",
      "external": false,
      "loc": "net/mptcp/protocol.c:1634",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated",
        "net/mptcp/protocol.c:__mptcp_check_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593662544,
      "name": "__mptcp_subflow_push_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
    },
    {
      "addr": 18446744071594640088,
      "name": "__mptcp_subflow_push_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mptcp_subflow_push_pending(struct sock * sk, struct sock * ssk, bool first)
```

```json
{
  "name": "__mptcp_subflow_push_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_subflow_push_pending",
      "external": false,
      "loc": "net/mptcp/protocol.c:1596",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated",
        "net/mptcp/protocol.c:__mptcp_check_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595593008,
      "name": "__mptcp_subflow_push_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
    },
    {
      "addr": 18446744071596369330,
      "name": "__mptcp_subflow_push_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mptcp_subflow_push_pending(struct sock * sk, struct sock * ssk, bool first)
```

```json
{
  "name": "__mptcp_subflow_push_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_subflow_push_pending",
      "external": false,
      "loc": "net/mptcp/protocol.c:1569",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated",
        "net/mptcp/protocol.c:__mptcp_check_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596102144,
      "name": "__mptcp_subflow_push_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
    },
    {
      "addr": 18446744071596898885,
      "name": "__mptcp_subflow_push_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mptcp_subflow_push_pending(struct sock * sk, struct sock * ssk, bool first)
```

```json
{
  "name": "__mptcp_subflow_push_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_subflow_push_pending",
      "external": false,
      "loc": "net/mptcp/protocol.c:1623",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated",
        "net/mptcp/protocol.c:__mptcp_check_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596970912,
      "name": "__mptcp_subflow_push_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
    },
    {
      "addr": 18446744071597823977,
      "name": "__mptcp_subflow_push_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __mptcp_subflow_push_pending(struct sock * sk, struct sock * ssk)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool first</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
