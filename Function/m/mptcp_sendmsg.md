# Function: <code>mptcp_sendmsg</code>

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
int mptcp_sendmsg(struct sock * sk, struct msghdr * msg, size_t len)
```

```json
{
  "name": "mptcp_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591087760,
      "name": "mptcp_sendmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:742",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591087760,
      "name": "mptcp_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1532
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
int mptcp_sendmsg(struct sock * sk, struct msghdr * msg, size_t len)
```

```json
{
  "name": "mptcp_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591164016,
      "name": "mptcp_sendmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:1582",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591164016,
      "name": "mptcp_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1631
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
int mptcp_sendmsg(struct sock * sk, struct msghdr * msg, size_t len)
```

```json
{
  "name": "mptcp_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591097296,
      "name": "mptcp_sendmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:1636",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591097296,
      "name": "mptcp_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2473
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
int mptcp_sendmsg(struct sock * sk, struct msghdr * msg, size_t len)
```

```json
{
  "name": "mptcp_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_sendmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:1672",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591940304,
      "name": "mptcp_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1866
    },
    {
      "addr": 18446744071592753285,
      "name": "mptcp_sendmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int mptcp_sendmsg(struct sock * sk, struct msghdr * msg, size_t len)
```

```json
{
  "name": "mptcp_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_sendmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:1705",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593666464,
      "name": "mptcp_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1262
    },
    {
      "addr": 18446744071594640261,
      "name": "mptcp_sendmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int mptcp_sendmsg(struct sock * sk, struct msghdr * msg, size_t len)
```

```json
{
  "name": "mptcp_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_sendmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:1700",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595603056,
      "name": "mptcp_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1662
    },
    {
      "addr": 18446744071596369760,
      "name": "mptcp_sendmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int mptcp_sendmsg(struct sock * sk, struct msghdr * msg, size_t len)
```

```json
{
  "name": "mptcp_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_sendmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:1697",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596111888,
      "name": "mptcp_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1728
    },
    {
      "addr": 18446744071596899109,
      "name": "mptcp_sendmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int mptcp_sendmsg(struct sock * sk, struct msghdr * msg, size_t len)
```

```json
{
  "name": "mptcp_sendmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_sendmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:1769",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596984432,
      "name": "mptcp_sendmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1911
    },
    {
      "addr": 18446744071597824483,
      "name": "mptcp_sendmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
int mptcp_sendmsg(struct sock * sk, struct msghdr * msg, size_t len)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
