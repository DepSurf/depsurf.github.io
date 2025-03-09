# Function: <code>inet6_netconf_fill_devconf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587023936,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:491",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587023936,
      "name": "inet6_netconf_fill_devconf.constprop.55",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587468928,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:495",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468928,
      "name": "inet6_netconf_fill_devconf.constprop.61",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587672224,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:522",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587672224,
      "name": "inet6_netconf_fill_devconf.constprop.61",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587820960,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:529",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587820960,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588351616,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:529",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588351616,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588707648,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:518",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588707648,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588928304,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:516",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588928304,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:513",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589370704,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
    },
    {
      "addr": 18446744071589401293,
      "name": "inet6_netconf_fill_devconf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589595200,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:513",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589595200,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590601360,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:513",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590601360,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590659856,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:513",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590659856,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590585264,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:515",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590585264,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591397104,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:523",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591397104,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593073648,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:522",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593073648,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594967776,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:522",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594967776,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595360528,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:521",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595360528,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596201408,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:525",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596201408,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503270024,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:513",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503270024,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235945592,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:513",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235945592,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297022864,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:513",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297022864,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279295978,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:513",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279295978,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589199568,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:513",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589199568,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588924560,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:513",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588924560,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589636432,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:513",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589636432,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet6_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589685376,
      "name": "inet6_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv6/addrconf.c:513",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_dump_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589685376,
      "name": "inet6_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv6_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```
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
