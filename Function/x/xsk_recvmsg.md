# Function: <code>xsk_recvmsg</code>

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
int xsk_recvmsg(struct socket * sock, struct msghdr * m, size_t len, int flags)
```

```json
{
  "name": "xsk_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591126784,
      "name": "xsk_recvmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:568",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591126784,
      "name": "xsk_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int xsk_recvmsg(struct socket * sock, struct msghdr * m, size_t len, int flags)
```

```json
{
  "name": "xsk_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591057088,
      "name": "xsk_recvmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:661",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591057088,
      "name": "xsk_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int xsk_recvmsg(struct socket * sock, struct msghdr * m, size_t len, int flags)
```

```json
{
  "name": "xsk_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_recvmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:661",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591899712,
      "name": "xsk_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
    },
    {
      "addr": 18446744071592751088,
      "name": "xsk_recvmsg.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int xsk_recvmsg(struct socket * sock, struct msghdr * m, size_t len, int flags)
```

```json
{
  "name": "xsk_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xsk_recvmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:691",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593619280,
      "name": "xsk_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    },
    {
      "addr": 18446744071594637685,
      "name": "xsk_recvmsg.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int xsk_recvmsg(struct socket * sock, struct msghdr * m, size_t len, int flags)
```

```json
{
  "name": "xsk_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595551984,
      "name": "xsk_recvmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:702",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595551984,
      "name": "xsk_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int xsk_recvmsg(struct socket * sock, struct msghdr * m, size_t len, int flags)
```

```json
{
  "name": "xsk_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596063440,
      "name": "xsk_recvmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:703",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596063440,
      "name": "xsk_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int xsk_recvmsg(struct socket * sock, struct msghdr * m, size_t len, int flags)
```

```json
{
  "name": "xsk_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596925216,
      "name": "xsk_recvmsg",
      "external": false,
      "loc": "net/xdp/xsk.c:976",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596925216,
      "name": "xsk_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int xsk_recvmsg(struct socket * sock, struct msghdr * m, size_t len, int flags)
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
