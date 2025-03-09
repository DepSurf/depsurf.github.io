# Function: <code>__sk_queue_drop_skb</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586845472,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:334",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586845472,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586968624,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:355",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586968624,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587466672,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:356",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587466672,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587771632,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:354",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587771632,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587905344,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:354",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587905344,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588213296,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:353",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588213296,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588418016,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:353",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588418016,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589284640,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:350",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284640,
      "name": "__sk_queue_drop_skb",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589283856,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:350",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589283856,
      "name": "__sk_queue_drop_skb",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589177568,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:350",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589177568,
      "name": "__sk_queue_drop_skb",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589900128,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:350",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589900128,
      "name": "__sk_queue_drop_skb",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591429856,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:347",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591429856,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593198617,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:345",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_kill_datagram"
      ],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593196032,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593658569,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:345",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_kill_datagram"
      ],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593655408,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594436505,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:346",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_kill_datagram"
      ],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594431264,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501938296,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:353",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501938296,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234692524,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:353",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234692524,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295353968,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:353",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295353968,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278242824,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:353",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278242824,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588024800,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:353",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588024800,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587737888,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:353",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587737888,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588356576,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:353",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588356576,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff_head * sk_queue, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```

```json
{
  "name": "__sk_queue_drop_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588492160,
      "name": "__sk_queue_drop_skb",
      "external": true,
      "loc": "net/core/datagram.c:353",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588492160,
      "name": "__sk_queue_drop_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int __sk_queue_drop_skb(struct sock * sk, struct sk_buff * skb, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff_head * sk_queue</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, skb, flags, destructor</code> ➡️ <code>sk, sk_queue, skb, flags, destructor</code>
</li>
</ul>
</details>
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
