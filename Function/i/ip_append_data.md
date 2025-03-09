# Function: <code>ip_append_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586569680,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1166",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586569680,
      "name": "ip_append_data.part.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071586573024,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587019297,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1164",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009120,
      "name": "ip_append_data.part.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071587016080,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587214990,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1205",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587204608,
      "name": "ip_append_data.part.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071587211760,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587347040,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1217",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587336752,
      "name": "ip_append_data.part.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071587343872,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587867033,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1149",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587861104,
      "name": "ip_append_data.part.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071587864032,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588212429,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1173",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588205632,
      "name": "ip_append_data.part.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071588209264,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588398781,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1199",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392576,
      "name": "ip_append_data.part.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071588395584,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588801000,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1288",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588794672,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071588797728,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589024634,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1296",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589018320,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071589021376,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589983711,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1295",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589977040,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071589980096,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590024479,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1302",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590017696,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071590020880,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589938924,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1306",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589932176,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071589935152,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590706028,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1305",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590699152,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071590702192,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592334809,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1305",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592327472,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071592330656,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594172567,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1322",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594164944,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071596336229,
      "name": "ip_append_data.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071596336280,
      "name": "ip_append_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071594168288,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594559585,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1340",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594553008,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071596865918,
      "name": "ip_append_data.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071596865969,
      "name": "ip_append_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071594556448,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595362209,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1344",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595355568,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071597790993,
      "name": "ip_append_data.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071597791044,
      "name": "ip_append_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071595359072,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502631084,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1296",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502621224,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446603336502627856,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235338008,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1296",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235331632,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 3235334772,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296229948,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1296",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296221744,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 13835058055296225712,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278778280,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1296",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278772896,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446743936278775592,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588631018,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1296",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588624704,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071588627760,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588343002,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1296",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588336688,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071588339744,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589067194,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1296",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589060880,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071589063936,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ip_append_data(struct sock * sk, struct flowi4 * fl4, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm_cookie * ipc, struct rtable * * rtp, unsigned int flags)
```

```json
{
  "name": "ip_append_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589106489,
      "name": "ip_append_data",
      "external": true,
      "loc": "net/ipv4/ip_output.c:1296",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply"
      ],
      "caller_func": [
        "net/ipv4/ip_output.c:ip_send_unicast_reply",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589100064,
      "name": "ip_append_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071589103232,
      "name": "ip_append_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
