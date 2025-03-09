# Function: <code>ip6_append_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, int hlimit, int tclass, struct ipv6_txoptions * opt, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, int dontfrag)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586998032,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1564",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586998032,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, const struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587444752,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1567",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444752,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, const struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587648144,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1594",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587648144,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, const struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587797648,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1597",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587797648,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, const struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588326496,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1546",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588326496,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, const struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588684096,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1558",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588684096,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588899712,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1588",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588899712,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589343488,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1652",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589343488,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589567696,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1656",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589567696,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590573312,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1726",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590573312,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590633296,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1765",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590633296,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590556672,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1797",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590556672,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1779",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592735815,
      "name": "ip6_append_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071591367968,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, size_t length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1800",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594622448,
      "name": "ip6_append_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071593041296,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, size_t length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1838",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596357114,
      "name": "ip6_append_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071594933552,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, size_t length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1857",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596885870,
      "name": "ip6_append_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071595325664,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, size_t length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1806",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597810420,
      "name": "ip6_append_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071596166928,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503237560,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1656",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503237560,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235910684,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1656",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235910684,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296982528,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1656",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296982528,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279271488,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1656",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279271488,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589172064,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1656",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589172064,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588897056,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1656",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588897056,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589608928,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1656",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589608928,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int ip6_append_data(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags)
```

```json
{
  "name": "ip6_append_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589657216,
      "name": "ip6_append_data",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1656",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589657216,
      "name": "ip6_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
<code>const struct sockcm_cookie * sockc</code>
</li>
<li>
<b>Param removed. </b>
<code>int hlimit</code>
</li>
<li>
<b>Param removed. </b>
<code>int tclass</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ipv6_txoptions * opt</code>
</li>
<li>
<b>Param removed. </b>
<code>int dontfrag</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, getfrag, from, length, transhdrlen, hlimit, tclass, opt, fl6, rt, flags, dontfrag</code> ➡️ <code>sk, getfrag, from, length, transhdrlen, ipc6, fl6, rt, flags, sockc</code>
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
<code>const struct sockcm_cookie * sockc</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int length</code> ➡️ <code>size_t length</code>
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
