# Function: <code>ip6_make_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, int hlimit, int tclass, struct ipv6_txoptions * opt, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, int dontfrag)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587005216,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1749",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587005216,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, const struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587451952,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1753",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587451952,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, const struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587655520,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1780",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587655520,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, const struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587804944,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1783",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587804944,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, const struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588334000,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1732",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588334000,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork, const struct sockcm_cookie * sockc)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588691408,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1744",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588691408,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588908400,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1775",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588908400,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589350336,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1839",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589350336,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589574592,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1843",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589574592,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590579600,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1913",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590579600,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590640064,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1952",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590640064,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590565968,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1984",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590565968,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1966",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592736341,
      "name": "ip6_make_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071591377552,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, size_t length, int transhdrlen, struct ipcm6_cookie * ipc6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1997",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594622973,
      "name": "ip6_make_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071593051776,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, size_t length, int transhdrlen, struct ipcm6_cookie * ipc6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:2035",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596357682,
      "name": "ip6_make_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071594944112,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, size_t length, int transhdrlen, struct ipcm6_cookie * ipc6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:2059",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596886328,
      "name": "ip6_make_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071595336656,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, size_t length, int transhdrlen, struct ipcm6_cookie * ipc6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596177440,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:2006",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596177440,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503249288,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1843",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503249288,
      "name": "ip6_make_skb",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235921508,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1843",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235921508,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296992848,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1843",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296992848,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279278010,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1843",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279278010,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589178960,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1843",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589178960,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588903952,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1843",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588903952,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589615824,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1843",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589615824,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
struct sk_buff * ip6_make_skb(struct sock * sk, int (*)(void *, char *, int, int, int, struct sk_buff *) getfrag, void * from, int length, int transhdrlen, struct ipcm6_cookie * ipc6, struct flowi6 * fl6, struct rt6_info * rt, unsigned int flags, struct inet_cork_full * cork)
```

```json
{
  "name": "ip6_make_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589664160,
      "name": "ip6_make_skb",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1843",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udpv6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589664160,
      "name": "ip6_make_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inet_cork_full * cork</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, getfrag, from, length, transhdrlen, ipc6, fl6, rt, flags, sockc</code> ➡️ <code>sk, getfrag, from, length, transhdrlen, ipc6, fl6, rt, flags, cork, sockc</code>
</li>
</ul>
</details>
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
<b>Param removed. </b>
<code>struct flowi6 * fl6</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, getfrag, from, length, transhdrlen, ipc6, fl6, rt, flags, cork</code> ➡️ <code>sk, getfrag, from, length, transhdrlen, ipc6, rt, flags, cork</code>
</li>
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
