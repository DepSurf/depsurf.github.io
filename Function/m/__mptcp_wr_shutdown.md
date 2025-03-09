# Function: <code>__mptcp_wr_shutdown</code>

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
void __mptcp_wr_shutdown(struct sock * sk)
```

```json
{
  "name": "__mptcp_wr_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591165648,
      "name": "__mptcp_wr_shutdown",
      "external": false,
      "loc": "net/mptcp/protocol.c:2526",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591165648,
      "name": "__mptcp_wr_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void __mptcp_wr_shutdown(struct sock * sk)
```

```json
{
  "name": "__mptcp_wr_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591099776,
      "name": "__mptcp_wr_shutdown",
      "external": false,
      "loc": "net/mptcp/protocol.c:2596",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591099776,
      "name": "__mptcp_wr_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void __mptcp_wr_shutdown(struct sock * sk)
```

```json
{
  "name": "__mptcp_wr_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_wr_shutdown",
      "external": false,
      "loc": "net/mptcp/protocol.c:2653",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591939088,
      "name": "__mptcp_wr_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071592753240,
      "name": "__mptcp_wr_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void __mptcp_wr_shutdown(struct sock * sk)
```

```json
{
  "name": "__mptcp_wr_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_wr_shutdown",
      "external": false,
      "loc": "net/mptcp/protocol.c:2797",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593664528,
      "name": "__mptcp_wr_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071594640191,
      "name": "__mptcp_wr_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void __mptcp_wr_shutdown(struct sock * sk)
```

```json
{
  "name": "__mptcp_wr_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_wr_shutdown",
      "external": false,
      "loc": "net/mptcp/protocol.c:2845",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595595184,
      "name": "__mptcp_wr_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071596369433,
      "name": "__mptcp_wr_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void __mptcp_wr_shutdown(struct sock * sk)
```

```json
{
  "name": "__mptcp_wr_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_wr_shutdown",
      "external": false,
      "loc": "net/mptcp/protocol.c:2843",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596104320,
      "name": "__mptcp_wr_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071596898970,
      "name": "__mptcp_wr_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void __mptcp_wr_shutdown(struct sock * sk)
```

```json
{
  "name": "__mptcp_wr_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_wr_shutdown",
      "external": false,
      "loc": "net/mptcp/protocol.c:2948",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596974320,
      "name": "__mptcp_wr_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071597824158,
      "name": "__mptcp_wr_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void __mptcp_wr_shutdown(struct sock * sk)
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
