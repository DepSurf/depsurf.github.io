# Function: <code>do_set_master</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586365591,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:1641",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:do_setlink"
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
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586797132,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:1806",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:do_setlink"
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
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586983645,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:1868",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:do_setlink"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_set_master(struct net_device * dev, int ifindex)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587106816,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:1937",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587106816,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587608416,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2108",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587608416,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587917920,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2222",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587917920,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588063136,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2338",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588063136,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588378592,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2343",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588378592,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588584992,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2364",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588584992,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589434192,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2450",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589434192,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589434688,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2493",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589434688,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589332048,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2487",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589332048,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590061472,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2497",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590061472,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591605776,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2551",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591605776,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593386560,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2591",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593386560,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593849216,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2649",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593849216,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594631248,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2681",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594631248,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502131360,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2364",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502131360,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234874840,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2364",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234874840,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295593904,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2364",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295593904,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278393162,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2364",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278393162,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588191728,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2364",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588191728,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587904560,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2364",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904560,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588523552,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2364",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588523552,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int do_set_master(struct net_device * dev, int ifindex, struct netlink_ext_ack * extack)
```

```json
{
  "name": "do_set_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588660832,
      "name": "do_set_master",
      "external": false,
      "loc": "net/core/rtnetlink.c:2364",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588660832,
      "name": "do_set_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int do_set_master(struct net_device * dev, int ifindex)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack * extack</code>
</li>
</ul>
</details>
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
