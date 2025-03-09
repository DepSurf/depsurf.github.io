# Function: <code>netlink_deliver_tap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586493340,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:262",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/netlink/af_netlink.c:netlink_unicast"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586949056,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:262",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587144032,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:262",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587274290,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:293",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587794328,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:295",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588136933,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:327",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588319682,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:327",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588705696,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:318",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588705696,
      "name": "netlink_deliver_tap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588929584,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:318",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588929584,
      "name": "netlink_deliver_tap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589817952,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:318",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817952,
      "name": "netlink_deliver_tap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589854176,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:319",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589854176,
      "name": "netlink_deliver_tap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589775315,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:327",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590534691,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:327",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592143350,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:331",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593967670,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:331",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594344598,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:331",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595144364,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:331",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502523176,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:318",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502523176,
      "name": "netlink_deliver_tap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235233572,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:318",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235233572,
      "name": "netlink_deliver_tap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296095968,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:318",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296095968,
      "name": "netlink_deliver_tap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
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
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278695016,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:318",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278695016,
      "name": "netlink_deliver_tap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588535968,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:318",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588535968,
      "name": "netlink_deliver_tap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588247968,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:318",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588247968,
      "name": "netlink_deliver_tap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588868144,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:318",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588868144,
      "name": "netlink_deliver_tap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```

```json
{
  "name": "netlink_deliver_tap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589009664,
      "name": "netlink_deliver_tap",
      "external": false,
      "loc": "net/netlink/af_netlink.c:318",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:__netlink_sendskb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589009664,
      "name": "netlink_deliver_tap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void netlink_deliver_tap(struct net * net, struct sk_buff * skb)
```
</details>
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
