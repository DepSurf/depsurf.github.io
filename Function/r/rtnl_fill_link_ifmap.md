# Function: <code>rtnl_fill_link_ifmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586374728,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1175",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586807156,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1207",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586994936,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1237",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587120264,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1237",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587624315,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1242",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587936025,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1338",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588059696,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1351",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588059696,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588375072,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1349",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588375072,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588581472,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1349",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588581472,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589432944,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1387",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589432944,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589433440,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1399",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589433440,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589330800,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1401",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589330800,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590060224,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1390",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590060224,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591642731,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1430",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593425690,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1441",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593891249,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1452",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594674398,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1459",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
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
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502127240,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1349",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502127240,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234871320,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1349",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234871320,
      "name": "rtnl_fill_link_ifmap",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295589568,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1349",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295589568,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278390168,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1349",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278390168,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588188208,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1349",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588188208,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587901040,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1349",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587901040,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588520032,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1349",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588520032,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "rtnl_fill_link_ifmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588657296,
      "name": "rtnl_fill_link_ifmap",
      "external": false,
      "loc": "net/core/rtnetlink.c:1349",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588657296,
      "name": "rtnl_fill_link_ifmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
```
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
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int rtnl_fill_link_ifmap(struct sk_buff * skb, struct net_device * dev)
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
