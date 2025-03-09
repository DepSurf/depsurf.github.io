# Function: <code>dev_validate_mtu</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588509719,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:7960",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588509584,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589380962,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:8373",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589380832,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589386802,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:8618",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589386672,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589283591,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:8877",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589283408,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590010935,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:8867",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext",
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590010752,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591549703,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:8632",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591549504,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593324083,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:8619",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593323872,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593785959,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:8625",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593785744,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594566596,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:8743",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594566384,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502043244,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:7960",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502043032,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234795004,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:7960",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234794800,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295490828,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:7960",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295490640,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278329914,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:7960",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278329758,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588116455,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:7960",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588116320,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587829287,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:7960",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587829152,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588448279,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:7960",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588448144,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
```

```json
{
  "name": "dev_validate_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588585191,
      "name": "dev_validate_mtu",
      "external": true,
      "loc": "net/core/dev.c:7960",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_mtu_ext"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588585056,
      "name": "dev_validate_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int dev_validate_mtu(struct net_device * dev, int new_mtu, struct netlink_ext_ack * extack)
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
