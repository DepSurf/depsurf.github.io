# Function: <code>udp_send_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586736432,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:799",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_push_pending_frames",
        "net/ipv4/udp.c:udp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586736432,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
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
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587182976,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:792",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587182976,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587383152,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:794",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587383152,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587517568,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:782",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587517568,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
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
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588040464,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:786",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588040464,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588393776,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:758",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588393776,
      "name": "udp_send_skb.isra.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 862
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588583600,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:827",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588583600,
      "name": "udp_send_skb.isra.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 865
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588994864,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:814",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588994864,
      "name": "udp_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 882
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589219392,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:814",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589219392,
      "name": "udp_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
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
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4, struct inet_cork * cork)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590190448,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:820",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590190448,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4, struct inet_cork * cork)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590239920,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:870",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590239920,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4, struct inet_cork * cork)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590153920,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:889",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590153920,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 903
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
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4, struct inet_cork * cork)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590934352,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:890",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590934352,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 901
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
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4, struct inet_cork * cork)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592576448,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:890",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592576448,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
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
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4, struct inet_cork * cork)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594438432,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:901",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendpage",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594438432,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
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
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4, struct inet_cork * cork)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594828640,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:916",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_splice_eof",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594828640,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4, struct inet_cork * cork)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595640320,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:886",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_splice_eof",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595640320,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502856808,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:814",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502856808,
      "name": "udp_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4, struct inet_cork * cork)
```

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235541064,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:814",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235541064,
      "name": "udp_send_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 844
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296513792,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:814",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296513792,
      "name": "udp_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278952084,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:814",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278952084,
      "name": "udp_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588825776,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:814",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588825776,
      "name": "udp_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588537712,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:814",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588537712,
      "name": "udp_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589261952,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:814",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589261952,
      "name": "udp_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_send_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589304944,
      "name": "udp_send_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:814",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_push_pending_frames"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589304944,
      "name": "udp_send_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4, struct inet_cork * cork)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int udp_send_skb(struct sk_buff * skb, struct flowi4 * fl4, struct inet_cork * cork)
```
</details>
</li>
</ul>
