# Function: <code>inet_netconf_fill_devconf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586775552,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:1750",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586775552,
      "name": "inet_netconf_fill_devconf.constprop.22",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587223104,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:1779",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587223104,
      "name": "inet_netconf_fill_devconf.constprop.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587423648,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:1779",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587423648,
      "name": "inet_netconf_fill_devconf.constprop.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587557824,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:1819",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587557824,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588081136,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:1828",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588081136,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588436912,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:1838",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588436912,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588629312,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:1973",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588629312,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2026",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589038768,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 634
    },
    {
      "addr": 18446744071589055529,
      "name": "inet_netconf_fill_devconf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589263280,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2021",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589263280,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590239216,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2027",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590239216,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590291920,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2026",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590291920,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590207760,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2027",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590207760,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590989376,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2028",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590989376,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592635040,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2035",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592635040,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 646
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594501184,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2036",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594501184,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 646
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594892800,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2039",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594892800,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595704112,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2070",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595704112,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502892072,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2021",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502892072,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235585904,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2021",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235585904,
      "name": "inet_netconf_fill_devconf",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296554192,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2021",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296554192,
      "name": "inet_netconf_fill_devconf",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278990616,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2021",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278990616,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588869456,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2021",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588869456,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588581392,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2021",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588581392,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589305840,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2021",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589305840,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
```

```json
{
  "name": "inet_netconf_fill_devconf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589347584,
      "name": "inet_netconf_fill_devconf",
      "external": false,
      "loc": "net/ipv4/devinet.c:2021",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_dump_devconf",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589347584,
      "name": "inet_netconf_fill_devconf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int inet_netconf_fill_devconf(struct sk_buff * skb, int ifindex, struct ipv4_devconf * devconf, u32 portid, u32 seq, int event, unsigned int flags, int type)
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
