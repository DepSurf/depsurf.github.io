# Function: <code>__mptcp_retrans</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __mptcp_retrans(struct sock * sk)
```

```json
{
  "name": "__mptcp_retrans",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591089312,
      "name": "__mptcp_retrans",
      "external": false,
      "loc": "net/mptcp/protocol.c:2305",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591089312,
      "name": "__mptcp_retrans",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
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
void __mptcp_retrans(struct sock * sk)
```

```json
{
  "name": "__mptcp_retrans",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_retrans",
      "external": false,
      "loc": "net/mptcp/protocol.c:2369",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591930016,
      "name": "__mptcp_retrans",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1039
    },
    {
      "addr": 18446744071592752689,
      "name": "__mptcp_retrans.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void __mptcp_retrans(struct sock * sk)
```

```json
{
  "name": "__mptcp_retrans",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_retrans",
      "external": false,
      "loc": "net/mptcp/protocol.c:2459",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593654512,
      "name": "__mptcp_retrans",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1122
    },
    {
      "addr": 18446744071594639635,
      "name": "__mptcp_retrans.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void __mptcp_retrans(struct sock * sk)
```

```json
{
  "name": "__mptcp_retrans",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_retrans",
      "external": false,
      "loc": "net/mptcp/protocol.c:2491",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595582256,
      "name": "__mptcp_retrans",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    },
    {
      "addr": 18446744071596368791,
      "name": "__mptcp_retrans.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void __mptcp_retrans(struct sock * sk)
```

```json
{
  "name": "__mptcp_retrans",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_retrans",
      "external": false,
      "loc": "net/mptcp/protocol.c:2502",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596090640,
      "name": "__mptcp_retrans",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1050
    },
    {
      "addr": 18446744071596898447,
      "name": "__mptcp_retrans.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void __mptcp_retrans(struct sock * sk)
```

```json
{
  "name": "__mptcp_retrans",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_retrans",
      "external": false,
      "loc": "net/mptcp/protocol.c:2578",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_release_cb",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596959408,
      "name": "__mptcp_retrans",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
    },
    {
      "addr": 18446744071597823572,
      "name": "__mptcp_retrans.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void __mptcp_retrans(struct sock * sk)
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
