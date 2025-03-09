# Function: <code>__mptcp_move_skbs</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool __mptcp_move_skbs(struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_move_skbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591082640,
      "name": "__mptcp_move_skbs",
      "external": false,
      "loc": "net/mptcp/protocol.c:955",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591082640,
      "name": "__mptcp_move_skbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool __mptcp_move_skbs(struct mptcp_sock * msk, unsigned int rcv)
```

```json
{
  "name": "__mptcp_move_skbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591155728,
      "name": "__mptcp_move_skbs",
      "external": false,
      "loc": "net/mptcp/protocol.c:1870",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591155728,
      "name": "__mptcp_move_skbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
bool __mptcp_move_skbs(struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_move_skbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591087760,
      "name": "__mptcp_move_skbs",
      "external": false,
      "loc": "net/mptcp/protocol.c:1933",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591087760,
      "name": "__mptcp_move_skbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool __mptcp_move_skbs(struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_move_skbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591931328,
      "name": "__mptcp_move_skbs",
      "external": false,
      "loc": "net/mptcp/protocol.c:1954",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591931328,
      "name": "__mptcp_move_skbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool __mptcp_move_skbs(struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_move_skbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593655984,
      "name": "__mptcp_move_skbs",
      "external": false,
      "loc": "net/mptcp/protocol.c:1988",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593655984,
      "name": "__mptcp_move_skbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
bool __mptcp_move_skbs(struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_move_skbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595586432,
      "name": "__mptcp_move_skbs",
      "external": false,
      "loc": "net/mptcp/protocol.c:1999",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595586432,
      "name": "__mptcp_move_skbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
bool __mptcp_move_skbs(struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_move_skbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596095600,
      "name": "__mptcp_move_skbs",
      "external": false,
      "loc": "net/mptcp/protocol.c:1993",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596095600,
      "name": "__mptcp_move_skbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
bool __mptcp_move_skbs(struct mptcp_sock * msk)
```

```json
{
  "name": "__mptcp_move_skbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mptcp_move_skbs",
      "external": false,
      "loc": "net/mptcp/protocol.c:2068",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_ioctl",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596964992,
      "name": "__mptcp_move_skbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    },
    {
      "addr": 18446744071597823733,
      "name": "__mptcp_move_skbs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool __mptcp_move_skbs(struct mptcp_sock * msk)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int rcv</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int rcv</code>
</li>
</ul>
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
