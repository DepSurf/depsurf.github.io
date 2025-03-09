# Function: <code>rtm_to_fib_config</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586815200,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:634",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_delroute",
        "net/ipv4/fib_frontend.c:inet_rtm_newroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586815200,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587264960,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:634",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587264960,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587465824,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:627",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587465824,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587601696,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:630",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587601696,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588125728,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:652",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588125728,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588480688,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:657",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588480688,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588674240,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:667",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674240,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589094432,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:726",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589094432,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589318608,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:727",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589318608,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590296048,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:719",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590296048,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 870
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590349056,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:719",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590349056,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 853
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590264928,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:721",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590264928,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 913
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591049648,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:721",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591049648,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 913
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592698400,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:724",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592698400,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594567760,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:724",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594567760,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 982
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594959584,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:727",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594959584,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 982
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595772064,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:727",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595772064,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 997
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502956368,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:727",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502956368,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235646164,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:727",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235646164,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296633568,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:727",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296633568,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279038948,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:727",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279038948,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588924784,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:727",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588924784,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588636720,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:727",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588636720,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589361168,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:727",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589361168,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
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
int rtm_to_fib_config(struct net * net, struct sk_buff * skb, struct nlmsghdr * nlh, struct fib_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_to_fib_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589403984,
      "name": "rtm_to_fib_config",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:727",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:inet_rtm_newroute",
        "net/ipv4/fib_frontend.c:inet_rtm_delroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589403984,
      "name": "rtm_to_fib_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack * extack</code>
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
