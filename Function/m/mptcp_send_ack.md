# Function: <code>mptcp_send_ack</code>

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
  "name": "mptcp_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591148141,
      "name": "mptcp_send_ack",
      "external": false,
      "loc": "net/mptcp/protocol.c:429",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mptcp_send_ack(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591077472,
      "name": "mptcp_send_ack",
      "external": false,
      "loc": "net/mptcp/protocol.c:421",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_retrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591077472,
      "name": "mptcp_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591930850,
      "name": "mptcp_send_ack",
      "external": false,
      "loc": "net/mptcp/protocol.c:456",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_retrans"
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
  "name": "mptcp_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593655486,
      "name": "mptcp_send_ack",
      "external": false,
      "loc": "net/mptcp/protocol.c:525",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_retrans"
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
  "name": "mptcp_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595583230,
      "name": "mptcp_send_ack",
      "external": false,
      "loc": "net/mptcp/protocol.c:517",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_retrans"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_send_ack(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_send_ack",
      "external": false,
      "loc": "net/mptcp/protocol.c:531",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_retrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596082816,
      "name": "mptcp_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071596897880,
      "name": "mptcp_send_ack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void mptcp_send_ack(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_send_ack",
      "external": false,
      "loc": "net/mptcp/protocol.c:519",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_retrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596951008,
      "name": "mptcp_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071597823203,
      "name": "mptcp_send_ack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void mptcp_send_ack(struct mptcp_sock * msk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void mptcp_send_ack(struct mptcp_sock * msk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void mptcp_send_ack(struct mptcp_sock * msk)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
