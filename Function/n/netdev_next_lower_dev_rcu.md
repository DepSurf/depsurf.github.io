# Function: <code>netdev_next_lower_dev_rcu</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586877033,
      "name": "netdev_next_lower_dev_rcu",
      "external": false,
      "loc": "net/core/dev.c:5716",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu",
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
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
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587001609,
      "name": "netdev_next_lower_dev_rcu",
      "external": false,
      "loc": "net/core/dev.c:5922",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu",
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
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
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587500265,
      "name": "netdev_next_lower_dev_rcu",
      "external": false,
      "loc": "net/core/dev.c:6063",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu",
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
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
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587804980,
      "name": "netdev_next_lower_dev_rcu",
      "external": false,
      "loc": "net/core/dev.c:6193",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu",
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
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
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587940532,
      "name": "netdev_next_lower_dev_rcu",
      "external": false,
      "loc": "net/core/dev.c:6768",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu",
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588249844,
      "name": "netdev_next_lower_dev_rcu",
      "external": false,
      "loc": "net/core/dev.c:6778",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu",
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588454919,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:6916",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588454512,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589322928,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:7307",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589322928,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589321792,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:7469",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589321792,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589217511,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:7728",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589217328,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589940921,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:7718",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589940768,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591474266,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:7239",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591474064,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593243754,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:7225",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593243536,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593704442,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:7230",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593704224,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594482778,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:7348",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594482560,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501979828,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:6916",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501979344,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234733996,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:6916",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234733536,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295407868,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:6916",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295407424,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278278250,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:6916",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278277918,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588061703,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:6916",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588061296,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587774791,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:6916",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587774384,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588393479,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:6916",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588393072,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```

```json
{
  "name": "netdev_next_lower_dev_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588529159,
      "name": "netdev_next_lower_dev_rcu",
      "external": true,
      "loc": "net/core/dev.c:6916",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_walk_all_lower_dev_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588528752,
      "name": "netdev_next_lower_dev_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct net_device * netdev_next_lower_dev_rcu(struct net_device * dev, struct list_head * * iter)
```
</details>
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
