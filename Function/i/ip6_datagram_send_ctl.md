# Function: <code>ip6_datagram_send_ctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipv6_txoptions * opt, int * hlimit, int * tclass, int * dontfrag)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587186096,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:685",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587186096,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1078
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6, struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639200,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:728",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639200,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6, struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587845552,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:740",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845552,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6, struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588002576,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:738",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002576,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6, struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588539360,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:745",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588539360,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6, struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588903600,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:740",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588903600,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589127056,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:739",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589127056,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589580752,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:737",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589580752,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1506
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589805104,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:737",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589805104,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1506
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590829888,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:737",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590829888,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1490
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
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590889920,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:753",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590889920,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1540
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
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590818976,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:753",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590818976,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1539
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
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591637760,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:753",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591637760,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1539
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
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593331456,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:753",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593331456,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1642
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
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595237088,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:759",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595237088,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1636
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
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595632480,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:759",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595632480,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1659
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
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596480288,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:759",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ping.c:ping_v6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596480288,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1682
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503510552,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:737",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503510552,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1608
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236165744,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:737",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236165744,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1616
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297303472,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:737",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297303472,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279482364,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:737",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279482364,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1274
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589409472,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:737",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589409472,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1506
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589134464,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:737",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589134464,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1506
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589846336,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:737",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589846336,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1506
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net * net, struct sock * sk, struct msghdr * msg, struct flowi6 * fl6, struct ipcm6_cookie * ipc6)
```

```json
{
  "name": "ip6_datagram_send_ctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589897616,
      "name": "ip6_datagram_send_ctl",
      "external": true,
      "loc": "net/ipv6/datagram.c:737",
      "file": "net/ipv6/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589897616,
      "name": "ip6_datagram_send_ctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1579
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ipcm6_cookie * ipc6</code>
</li>
<li>
<b>Param added. </b>
<code>struct sockcm_cookie * sockc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ipv6_txoptions * opt</code>
</li>
<li>
<b>Param removed. </b>
<code>int * hlimit</code>
</li>
<li>
<b>Param removed. </b>
<code>int * tclass</code>
</li>
<li>
<b>Param removed. </b>
<code>int * dontfrag</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct sockcm_cookie * sockc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
