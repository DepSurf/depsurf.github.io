# Function: <code>rtnl_dev_get</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rtnl_dev_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589465837,
      "name": "rtnl_dev_get",
      "external": false,
      "loc": "net/core/rtnetlink.c:2844",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rtnl_dev_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589468493,
      "name": "rtnl_dev_get",
      "external": false,
      "loc": "net/core/rtnetlink.c:2948",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rtnl_dev_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589366847,
      "name": "rtnl_dev_get",
      "external": false,
      "loc": "net/core/rtnetlink.c:2946",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink"
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
  "name": "rtnl_dev_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590095455,
      "name": "rtnl_dev_get",
      "external": false,
      "loc": "net/core/rtnetlink.c:2956",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * rtnl_dev_get(struct net * net, struct nlattr * * tb)
```

```json
{
  "name": "rtnl_dev_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591645780,
      "name": "rtnl_dev_get",
      "external": false,
      "loc": "net/core/rtnetlink.c:3024",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591605968,
      "name": "rtnl_dev_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
struct net_device * rtnl_dev_get(struct net * net, struct nlattr * * tb)
```

```json
{
  "name": "rtnl_dev_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593428884,
      "name": "rtnl_dev_get",
      "external": false,
      "loc": "net/core/rtnetlink.c:3064",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593386768,
      "name": "rtnl_dev_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
struct net_device * rtnl_dev_get(struct net * net, struct nlattr * * tb)
```

```json
{
  "name": "rtnl_dev_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593893903,
      "name": "rtnl_dev_get",
      "external": false,
      "loc": "net/core/rtnetlink.c:3126",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593849424,
      "name": "rtnl_dev_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
struct net_device * rtnl_dev_get(struct net * net, struct nlattr * * tb)
```

```json
{
  "name": "rtnl_dev_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594677154,
      "name": "rtnl_dev_get",
      "external": false,
      "loc": "net/core/rtnetlink.c:3158",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594631824,
      "name": "rtnl_dev_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct net_device * rtnl_dev_get(struct net * net, struct nlattr * * tb)
```
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
