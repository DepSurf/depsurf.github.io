# Function: <code>__skb_free_datagram_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586661920,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:304",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586661920,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586847008,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:312",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586847008,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586971232,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:335",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586971232,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587469840,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:336",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587469840,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587774800,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:334",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587774800,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587907024,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:334",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587907024,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588216144,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:333",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216144,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588420976,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:333",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588420976,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589285392,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:330",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589285392,
      "name": "__skb_free_datagram_locked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071589285600,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589283648,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:330",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589283648,
      "name": "__skb_free_datagram_locked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071589284096,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589177808,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:330",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589177808,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589900368,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:330",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589900368,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591430080,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:327",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591430080,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593196272,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:326",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593196272,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593655648,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:326",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593655648,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594431504,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:327",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594431504,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501937168,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:333",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501937168,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234695520,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:333",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234695520,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295354800,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:333",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295354800,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278245664,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:333",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278245664,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588027760,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:333",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588027760,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587740848,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:333",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587740848,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588359536,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:333",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588359536,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```

```json
{
  "name": "__skb_free_datagram_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588495088,
      "name": "__skb_free_datagram_locked",
      "external": true,
      "loc": "net/core/datagram.c:333",
      "file": "net/core/datagram.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588495088,
      "name": "__skb_free_datagram_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void __skb_free_datagram_locked(struct sock * sk, struct sk_buff * skb, int len)
```
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
