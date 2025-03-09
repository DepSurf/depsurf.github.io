# Function: <code>mptcp_recvmsg</code>

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
int mptcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "mptcp_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591084624,
      "name": "mptcp_recvmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:974",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591084624,
      "name": "mptcp_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 963
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
int mptcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "mptcp_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591156832,
      "name": "mptcp_recvmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:1915",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591156832,
      "name": "mptcp_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1462
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
int mptcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "mptcp_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591091584,
      "name": "mptcp_recvmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:1977",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591091584,
      "name": "mptcp_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1799
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
int mptcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "mptcp_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_recvmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:1998",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591931808,
      "name": "mptcp_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2074
    },
    {
      "addr": 18446744071592752795,
      "name": "mptcp_recvmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int mptcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "mptcp_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_recvmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:2052",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593656480,
      "name": "mptcp_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2327
    },
    {
      "addr": 18446744071594639719,
      "name": "mptcp_recvmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int mptcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "mptcp_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_recvmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:2063",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595586944,
      "name": "mptcp_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2225
    },
    {
      "addr": 18446744071596368961,
      "name": "mptcp_recvmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int mptcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "mptcp_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_recvmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:2057",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596096112,
      "name": "mptcp_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2224
    },
    {
      "addr": 18446744071596898541,
      "name": "mptcp_recvmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int mptcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "mptcp_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_recvmsg",
      "external": false,
      "loc": "net/mptcp/protocol.c:2132",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596965808,
      "name": "mptcp_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2219
    },
    {
      "addr": 18446744071597823754,
      "name": "mptcp_recvmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int mptcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nonblock</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, msg, len, nonblock, flags, addr_len</code> ➡️ <code>sk, msg, len, flags, addr_len</code>
</li>
</ul>
</details>
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
